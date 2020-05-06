<template>
  <div>
      <base-header
      class="header pb-8 pt-5 pt-lg-8 d-flex align-items-center"
      style="min-height: 600px; background-image: url(img/theme/profile-cover3.jpg); background-size: cover; background-position: center top;"
    >
    <span class="mask bg-gradient-success opacity-4"></span>
      <div class="row">
        <div class="col-xl-3 col-lg-6">
          <stats-card
            title="TRÁFEGO TOTAL MÁQUINARIO"
            type="gradient-red"
            sub-title="350,897"
            icon="fa fa-truck"
            class="mb-4 mb-xl-0"
          >
            <template slot="footer">
              <span class="text-success mr-2">
                <i class="fa fa-arrow-up"></i> 73.48%
              </span>
              <span class="text-nowrap">Desde último Mês</span>
            </template>
          </stats-card>
        </div>
        <div class="col-xl-3 col-lg-6">
          <stats-card
            title="TRÁFEGO TOTAL MÁQUINARIO"
            type="gradient-orange"
            sub-title="2,356"
            icon="fa fa-truck"
            class="mb-4 mb-xl-0"
          >
            <template slot="footer">
              <span class="text-success mr-2">
                <i class="fa fa-arrow-up"></i> 12.18%
              </span>
              <span class="text-nowrap">Desde última Semana</span>
            </template>
          </stats-card>
        </div>
        <div class="col-xl-3 col-lg-6">
          <stats-card
            title="COMBUSTIVEL TOTAL GASTO"
            type="gradient-green"
            sub-title="924"
            icon="fa fa-tint"
            class="mb-4 mb-xl-0"
          >
            <template slot="footer">
              <span class="text-danger mr-2">
                <i class="fa fa-arrow-down"></i> 55.72%
              </span>
              <span class="text-nowrap">Desde último Més</span>
            </template>
          </stats-card>
        </div>
        <div class="col-xl-3 col-lg-6">
          <stats-card
            title="DESEMPENHO MÁQUINARIO"
            type="gradient-info"
            sub-title="49,65%"
            icon="fa fa-truck"
            class="mb-4 mb-xl-0"
          >
            <template slot="footer">
              <span class="text-success mr-2">
                <i class="fa fa-arrow-up"></i> 54.8%
              </span>
              <span class="text-nowrap">Desde último Més</span>
            </template>
          </stats-card>
        </div>
      </div>
    </base-header>

    <div class="container-fluid mt--7">
      <div class="row mt-5">
        <div class="col">
          <projects-table type="dark" title="MÁQUINARIO"></projects-table>
        </div>
      </div>
    </div>
    <br/><br/><br/><br/><br/><br/>
  </div>
</template>
<script>
import ProjectsTable from "./Tables/ProjectsTable";
export default {
  name: "Maquinas",
  components: {
    ProjectsTable
  }
};
</script>
<style></style>
