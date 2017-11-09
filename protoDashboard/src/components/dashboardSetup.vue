<template>
    <form>
        <div class="container-fluid">
            <div class="row">
                <h2 class="text-left col-xs-offset-1 col-sm-offset-1 col-md-offset-1 col-lg-offset-1">Dashboard Setup</h2>
            </div>
            <div class="row">
                <div :class="bClass.noneClass"></div>
                <div class="text-left col-xs-10 col-sm-10 col-md-10 col-lg-10">
                    <div class="form-group">
                        <label>Nome:</label>
                    </div>
                </div>
            </div>
            <div class="row">
                <div :class="bClass.noneClass"></div>
                <div class="col-xs-10 col-sm-10 col-md-10 col-lg-10">
                    <div class="form-group">
                        <input id="nomeDashboardSetup" type="text" placeholder="Nome" class="form-control" v-model="nameDashboard">
                    </div>
                </div>
            </div>
            <div class="row">
                <div :class="bClass.noneClass"></div>
                <div class="text-left col-xs-10 col-sm-10 col-md-10 col-lg-10">
                    <label>Select a layout:</label>
                </div>
            </div>
            <div class="row">
                <div :class="bClass.noneClass"></div>
                <!-- <div :class="bClass.svgClass">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" version="1.1" :width="svg.width" :height="svg.height" :style="svg.style">
                            <g id="Document" fill="none" stroke="black" font-family="Times New Roman" font-size="16" transform="scale(1 -1)">
                                <g id="Spread" transform="translate(0 -105.975)">
                                    <path :d="svg.d" fill-rule="evenodd" stroke="none" stroke-width="0.5" :fill="svg.fill" marker-start="none" marker-end="none" stroke-miterlimit="79.8403193612775"/>
                                </g>
                            </g>
                        </svg>
                    </span>
                </div> -->
                <div :class="bClass.svgClass">
                    <span>
                        <svg xmlns="http://www.w3.org/2000/svg" version="1.1" stroke-width="0.50099999" stroke-linejoin="bevel" overflow="visible" fill-rule="evenodd" width="161.55pt" height="106pt" viewBox="0 0 161.55 106">
                            <!-- <g style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel" id="g3686" transform="matrix(1.5389468,0,0,1.0018827,27.390897,0.20331935)"> -->
                                <g font-size="16px" font-family="Times New Roman" fill="none" stroke="#000000" transform="scale(1 -1)" id="Document-4">
                                <!-- transform="matrix(0.99223123,0,0,-0.99808441,-17.813751,-0.1886765)" -->
                                    <g transform="translate(0,-105.975)">
                                        <g style="fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677" stroke-miterlimit="79.8403193612775"
                                            id="Group">
                                            <path :fill="svgFill" style="marker-start:none;marker-end:none" inkscape:connector-curvature="0" id="path4501" d="M 0.017,-0.011 V 105.986 H 49.209 V -0.011 Z M 44.823,4.375 V 101.6 H 4.403 V 4.375 Z m 11.793,-4.386 v 105.997 h 49.193 V -0.011 Z m 44.807,4.386 V 101.6 H 61.002 V 4.375 Z"/>
                                        </g>
                                    </g>
                                </g>
                            <!-- </g> -->
                        </svg>
                    </span>
                </div>
                <div :class="bClass.svgClass">
                    <span>
                        <svg stroke-width="0.501" stroke-linejoin="bevel" fill-rule="evenodd" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" version="1.1" overflow="visible" width="161.55pt" height="105.975pt" viewBox="0 0 161.55 105.975">
                            <g id="Document" fill="none" stroke="black" font-family="Times New Roman" font-size="16" transform="scale(1 -1)">
                                <g id="Spread" transform="translate(0 -105.975)">
                                    <g id="Layer 1">
                                        <g id="Group" fill-rule="evenodd" stroke="none" stroke-width="0.5" :fill="svgFill" stroke-miterlimit="79.8403193612775">
                                            <path d="M 0.001,-0.01 L 0.001,105.987 L 105.369,105.987 L 105.369,-0.01 L 0.001,-0.01 Z M 100.983,4.376 L 100.983,101.601 L 4.387,101.601 L 4.387,4.376 L 100.983,4.376 Z M 112.358,-0.013 L 112.358,105.984 L 161.55,105.984 L 161.55,-0.013 L 112.358,-0.013 Z M 157.164,4.373 L 157.164,101.598 L 116.744,101.598 L 116.744,4.373 L 157.164,4.373 Z" marker-start="none" marker-end="none"/>
                                        </g>
                                    </g>
                                </g>
                            </g>
                        </svg>
                    </span> 
                </div>
                <div :class="bClass.svgClass">
                    <span>
                        <svg stroke-width="0.501" stroke-linejoin="bevel" fill-rule="evenodd" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" version="1.1" overflow="visible" width="161.55pt" height="105.975pt" viewBox="0 0 161.55 105.975">
                            <g id="Document" fill="none" stroke="black" font-family="Times New Roman" font-size="16" transform="scale(1 -1)">
                                <g id="Spread" transform="translate(0 -105.975)">
                                    <g id="Layer 1">
                                        <g id="Group" fill-rule="evenodd" stroke="none" stroke-width="0.5" :fill="svgFill" stroke-miterlimit="79.8403193612775">
                                            <path d="M 56.182,-0.01 L 56.182,105.987 L 161.55,105.987 L 161.55,-0.01 L 56.182,-0.01 Z M 157.164,4.376 L 157.164,101.601 L 60.568,101.601 L 60.568,4.376 L 157.164,4.376 Z M 0,-0.013 L 0,105.984 L 49.193,105.984 L 49.193,-0.013 L 0,-0.013 Z M 44.807,4.373 L 44.807,101.598 L 4.386,101.598 L 4.386,4.373 L 44.807,4.373 Z" marker-start="none" marker-end="none"/>
                                        </g>
                                    </g>
                                </g>
                            </g>
                        </svg>
                    </span>
                </div>
                <div :class="bClass.svgClass">
                    <span>
                        <svg stroke-width="0.501" stroke-linejoin="bevel" fill-rule="evenodd" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg" version="1.1" overflow="visible" width="161.1pt" height="105.975pt" viewBox="0 0 161.1 105.975">
                            <g id="Document" fill="none" stroke="black" font-family="Times New Roman" font-size="16" transform="scale(1 -1)">
                                <g id="Spread" transform="translate(0 -105.975)">
                                    <g id="Layer 1">
                                        <path d="M 0.012,-0.011 L 0.012,105.986 L 161.088,105.986 L 161.088,-0.011 L 0.012,-0.011 Z M 156.702,4.375 L 156.702,101.6 L 4.398,101.6 L 4.398,4.375 L 156.702,4.375 Z" stroke-width="0.5" stroke="none" :fill="svgFill" fill-rule="evenodd" marker-start="none" marker-end="none" stroke-miterlimit="79.8403193612775"/>
                                    </g>
                                </g>
                            </g>
                        </svg>
                    </span>
                </div>
            </div>

            <div class="row">
                <div :class="bClass.noneClass"></div>
                <div :class="bClass.dropdownsClass">
                    <div class="form-group">
                        <div class="text-left">
                            <label>
                                Team:
                            </label>
                        </div>
                        <select class="form-control" multiple>
                            <option v-for="team in teams" :value="team">{{ team }}</option>
                        </select>
                    </div>
                </div>
                <div :class="bClass.dropdownsClass">
                    <div class="form-group">
                        <div class="text-left">
                            <label>
                                Team Member:
                            </label>
                        </div>
                        <select class="form-control" multiple>
                            <option v-for="teamMember in teamMembers" :value="teamMember">{{ teamMember }}</option>
                        </select>
                    </div>
                </div>
            </div>
            <div class="row">
                <div :class="bClass.noneClass"></div>
                <div class="col-xs-10 col-sm-10 col-md-10 col-lg-10">
                    <button class="btn btn-primary">Create</button>
                    <button class="btn btn-primary">Cancel</button>    
                </div>
            </div>
        </div>
    </form>
</template>

<script>
export default {
    data() {
        return {
            bClass: {
                svgClass: 'col-xs-2 col-sm-2 col-md-2 col-lg-2',
                noneClass: 'col-xs-1 col-sm-1 col-md-1 col-lg-1',
                dropdownsClass: 'col-xs-5 col-sm-5 col-md-5 col-lg-5'
            },
            teams: ['Iron', 'Captan', "Lind", "Kelvin"],
            teamMembers: [],
            nameDashboard: '',
            svgFill: '#666666',
            listSvg: [
                {
                    d: 'M 0,-0.01 L 0,105.987 L 49.193,105.987 L 49.193,-0.01 L 0,-0.01 Z M 44.807,4.376 L 44.807,101.601 L 4.386,101.601 L 4.386,4.376 L 44.807,4.376 Z M 56.179,-0.01 L 56.179,105.987 L 105.371,105.987 L 105.371,-0.01 L 56.179,-0.01 Z M 100.985,4.376 L 100.985,101.601 L 60.565,101.601 L 60.565,4.376 L 100.985,4.376 Z M 112.357,-0.013 L 112.357,105.984 L 161.55,105.984 L 161.55,-0.013 L 112.357,-0.013 Z M 157.164,4.373 L 157.164,101.598 L 116.743,101.598 L 116.743,4.373 L 157.164,4.373 Z',
                    titulo: '3-col',
                    fill: '#666666',
                    overflow: "visible",
                    width: "161.55pt",
                    height: "105.975pt",
                    style: "stroke-width:0.501;stroke-linejoin:bevel;overflow:visible;fill-rule:evenodd;viewBox:0 0 161.55 105.975"
                },{
                    titulo: '2-col',
                    fill: '#666666'
                },{
                    titulo: '2-col 1-big 1-small',
                    fill: '#666666'
                },{
                    titulo: '2-col 1-small 1-big',
                    fill: '#666666'
                },{
                    titulo: '1-col',
                    fill: '#666666'
                },
            ]
        }
    }
  
}
</script>

<style scoped>
svg {
    width: 75%;
    /* margin-left: 20%;
    margin-right: 20%; */
}
label {
    text-align: left;
}
</style>
