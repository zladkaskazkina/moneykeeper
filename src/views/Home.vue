<template>
  <div>
    <div class="page-title">
      <h3>Account</h3>

      <button class="btn waves-effect waves-light btn-small">
        <i class="material-icons">refresh</i>
      </button>
    </div>

    <div class="row">
      <div class="col s12 m6 l4">
        <div class="card light-blue bill-card">
          <div class="card-content white-text">
            <span class="card-title">Account in $</span>

            <p class="currency-line">
              <span>12.0 $</span>
            </p>
          </div>
        </div>
      </div>

      <div class="col s12 m6 l8">
        <div class="card orange darken-3 bill-card">
          <div class="card-content white-text">
            <div class="card-header">
              <span class="card-title">Exchange Rates</span>
            </div>
            <table>
              <thead>
                <tr>
                  <th>Currency</th>
                  <th>Rate</th>
                  <th>Date</th>
                </tr>
              </thead>

              <tbody>
                <tr>
                  <td>$</td>
                  <td>121</td>
                  <td>12.12.12</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src

export default {
  name: "Home",
  components: {}
};
</script>
