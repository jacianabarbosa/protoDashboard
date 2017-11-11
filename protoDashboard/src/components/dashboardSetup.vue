<template>
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
                <div :class="bClass.noneClass">
                </div>
                <div :class="bClass.svgClass">
                    <span v-on:click="changeColor(0)">
                        <!-- Azul -->
                        <div v-show="listSvg[0]">
                            <svg xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.55pt" height="106pt"
                                viewBox="0 0 161.55 106" id="svg6176" sodipodi:docname="3-col.svg" style="display:inline;overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                >
                                <metadata id="metadata6180">
                                    <rdf:RDF>
                                        <cc:Work rdf:about="">
                                            <dc:format>image/svg+xml</dc:format>
                                            <dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
                                            <dc:title></dc:title>
                                        </cc:Work>
                                    </rdf:RDF>
                                </metadata>
                                <sodipodi:namedview pagecolor="#ffffff" bordercolor="#0460ad" borderopacity="1" objecttolerance="10" gridtolerance="10" guidetolerance="10"
                                    inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="745" id="namedview6178"
                                    showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="1.6702053"
                                    inkscape:cx="75.967375" inkscape:cy="70.649999" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1"
                                    inkscape:current-layer="svg6176" />
                                <defs id="defs6165" />
                                <g id="Document" font-size="16" transform="matrix(1,0,0,-1,0,0.012)" style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000">
                                    <g id="Spread" transform="translate(0,-105.975)">
                                        <g id="Layer 1">
                                            <path d="M 0,-0.01 V 105.987 H 49.193 V -0.01 Z m 44.807,4.386 v 97.225 H 4.386 V 4.376 Z" stroke-miterlimit="79.8403193612775"
                                                id="path6167" inkscape:connector-curvature="0"  style="fill:#0460ad;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
                                            />
                                            <path d="m 56.179,-0.01 v 105.997 h 49.192 V -0.01 Z m 44.806,4.386 v 97.225 H 60.565 V 4.376 Z" stroke-miterlimit="79.8403193612775"
                                                id="path6169" inkscape:connector-curvature="0" style="fill:#0460ad;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
                                            />
                                            <path d="M 112.357,-0.013 V 105.984 H 161.55 V -0.013 Z m 44.807,4.386 v 97.225 H 116.743 V 4.373 Z" stroke-miterlimit="79.8403193612775"
                                                id="path6171" inkscape:connector-curvature="0" style="fill:#0460ad;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
                                            />
                                        </g>
                                    </g>
                                </g>
                            </svg>
                        </div>
                        <!-- Cinza -->
                        <svg v-show="!listSvg[0]" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                            xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                            xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.55pt" height="106pt"
                            viewBox="0 0 161.55 106" id="svg6176" sodipodi:docname="3-col.svg" style="display:inline;overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                            >
                            <metadata id="metadata6180">
                                <rdf:RDF>
                                    <cc:Work rdf:about="">
                                        <dc:format>image/svg+xml</dc:format>
                                        <dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
                                        <dc:title></dc:title>
                                    </cc:Work>
                                </rdf:RDF>
                            </metadata>
                            <sodipodi:namedview pagecolor="#ffffff" bordercolor="#666666" borderopacity="1" objecttolerance="10" gridtolerance="10" guidetolerance="10"
                                inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="745" id="namedview6178"
                                showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="1.6702053"
                                inkscape:cx="75.967375" inkscape:cy="70.649999" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1"
                                inkscape:current-layer="svg6176" />
                            <defs id="defs6165" />
                            <g id="Document" font-size="16" transform="matrix(1,0,0,-1,0,0.012)" style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000">
                                <g id="Spread" transform="translate(0,-105.975)">
                                    <g id="Layer 1">
                                        <path d="M 0,-0.01 V 105.987 H 49.193 V -0.01 Z m 44.807,4.386 v 97.225 H 4.386 V 4.376 Z" stroke-miterlimit="79.8403193612775"
                                            id="path6167" inkscape:connector-curvature="0"  style="fill:#666666;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
                                        />
                                        <path d="m 56.179,-0.01 v 105.997 h 49.192 V -0.01 Z m 44.806,4.386 v 97.225 H 60.565 V 4.376 Z" stroke-miterlimit="79.8403193612775"
                                            id="path6169" inkscape:connector-curvature="0" style="fill:#666666;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
                                        />
                                        <path d="M 112.357,-0.013 V 105.984 H 161.55 V -0.013 Z m 44.807,4.386 v 97.225 H 116.743 V 4.373 Z" stroke-miterlimit="79.8403193612775"
                                            id="path6171" inkscape:connector-curvature="0" style="fill:#666666;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
                                        />
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
</template>

<script>
export default {
    props: ['selectedLayout'],
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
            listSvg: [false, false, false, false, false],
        }
    },
    methods: {
        changeColor(pos) {
            console.log(this.listSvg[pos]);
             this.listSvg[pos] = !this.listSvg[pos];
        }
    },
    watch: {
        selectedLayout: () => {
            this.listSvg = [false, false, false, false, false];
            if (selectedLayout != '')
                this.listSvg[selectedLayout] = true;
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

#path6167{
    fill: #666666;
    fill-rule:evenodd;
    stroke:none;
    stroke-width:0.5;
    stroke-miterlimit:79.84031677;
    marker-start:none;
    marker-end:none
}
</style>
