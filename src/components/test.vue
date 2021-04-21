<template>
  <div class="info-card">
        <div class="row">
            <div class="col-12  align-items-center">
                <div class="row chart-bar">
                    <div class="chart-type">
                        <button class="btn btn-primary btn-sm mr-2" :class="[{'active': chartType==='cs'}]" @click="toCandleStickChart">Candlestick Chart</button>
                        <button class="btn btn-primary btn-sm" :class="[{'active': chartType==='lc'}]" @click="toLineChart">Line Chart</button>
                    </div>
                </div>
            </div>
            <div class="chart-panel col" ref="chartdiv" id="chartdiv">

            </div>
</template>

<script>
export default {

}
</script>

<style>

</style>