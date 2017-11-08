<template>
    <form>
        <div class="container">
            <!-- Diminuir o tamanho disso. -->
            <div class="row">
                <div class="col-xs-6 col-sm-5">
                    <div class="form-group">
                        <label>Nome:</label>
                        <input id="nomeDashboardSetup" type="text" placeholder="Nome" class="form-control">
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-xs-6 col-sm-5">
                    <div class="form-goup">
                        <label>Select a layout:</label>
                        <br/>
                        <!-- <div >
                            <span class="img_svg" on-click="selctImage0">
                                <svg style="display: inline" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.55pt" height="106pt"
                                    viewBox="0 0 161.55 106" id="svg6176" sodipodi:docname="3-col.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.0 r15299">
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
                                                    id="path6167" inkscape:connector-curvature="0" style="fill:#666666;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
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
                                <svg style="display: none" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.55pt" height="106pt"
                                    viewBox="0 0 161.55 106" id="svg6176" sodipodi:docname="3-col.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.0 r15299">
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
                                                    id="path6167" inkscape:connector-curvature="0" style="fill:#0460ad;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
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
                            </span>
                            <span class="img_svg" on-click="selctImage1">
                                <svg style="display: inline" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.55pt" height="106pt"
                                    viewBox="0 0 161.55 106" id="svg6176" sodipodi:docname="2-col.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.1 r15371">
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
                                        inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="715" id="namedview6178"
                                        showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="2.8284271"
                                        inkscape:cx="112.90087" inkscape:cy="70.816328" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1"
                                        inkscape:current-layer="svg6176" />
                                    <defs id="defs6165" />
                                    <g style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel" id="g3686" transform="matrix(1.5389468,0,0,1.0018827,27.390897,0.20331935)">
                                        <g style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000" transform="matrix(0.99223123,0,0,-0.99808441,-17.813751,-0.1886765)"
                                            font-size="16" id="Document-4">
                                            <g transform="translate(0,-105.975)" id="Spread-3">
                                                <g id="Layer 1-6">
                                                    <g style="fill:#666666;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677" stroke-miterlimit="79.8403193612775"
                                                        id="Group">
                                                        <path style="marker-start:none;marker-end:none" inkscape:connector-curvature="0" id="path4501" d="M 0.017,-0.011 V 105.986 H 49.209 V -0.011 Z M 44.823,4.375 V 101.6 H 4.403 V 4.375 Z m 11.793,-4.386 v 105.997 h 49.193 V -0.011 Z m 44.807,4.386 V 101.6 H 61.002 V 4.375 Z"
                                                            class="teste" />
                                                    </g>
                                                </g>
                                            </g>
                                        </g>
                                    </g>
                                </svg>
                                <svg style="display: none" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.55pt" height="106pt"
                                    viewBox="0 0 161.55 106" id="svg6176" sodipodi:docname="2-col.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.1 r15371">
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
                                        inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="715" id="namedview6178"
                                        showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="2.8284271"
                                        inkscape:cx="112.90087" inkscape:cy="70.816328" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1"
                                        inkscape:current-layer="svg6176" />
                                    <defs id="defs6165" />
                                    <g style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel" id="g3686" transform="matrix(1.5389468,0,0,1.0018827,27.390897,0.20331935)">
                                        <g style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000" transform="matrix(0.99223123,0,0,-0.99808441,-17.813751,-0.1886765)"
                                            font-size="16" id="Document-4">
                                            <g transform="translate(0,-105.975)" id="Spread-3">
                                                <g id="Layer 1-6">
                                                    <g style="fill:#0460ad;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677" stroke-miterlimit="79.8403193612775"
                                                        id="Group">
                                                        <path style="marker-start:none;marker-end:none" inkscape:connector-curvature="0" id="path4501" d="M 0.017,-0.011 V 105.986 H 49.209 V -0.011 Z M 44.823,4.375 V 101.6 H 4.403 V 4.375 Z m 11.793,-4.386 v 105.997 h 49.193 V -0.011 Z m 44.807,4.386 V 101.6 H 61.002 V 4.375 Z"
                                                            class="teste" />
                                                    </g>
                                                </g>
                                            </g>
                                        </g>
                                    </g>
                                </svg>
                            </span>
                            <span class="img_svg" on-click="selctImage2">
                                <svg style="display: inline" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.549pt" height="106pt"
                                    viewBox="0 0 161.54899 106" id="svg5616" sodipodi:docname="2col-1col.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.0 r15299">
                                    <metadata id="metadata5620">
                                        <rdf:RDF>
                                            <cc:Work rdf:about="">
                                                <dc:format>image/svg+xml</dc:format>
                                                <dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
                                                <dc:title></dc:title>
                                            </cc:Work>
                                        </rdf:RDF>
                                    </metadata>
                                    <sodipodi:namedview pagecolor="#ffffff" bordercolor="#666666" borderopacity="1" objecttolerance="10" gridtolerance="10" guidetolerance="10"
                                        inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="745" id="namedview5618"
                                        showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="1.6702053"
                                        inkscape:cx="107.7" inkscape:cy="70.65" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1" inkscape:current-layer="svg5616"
                                    />
                                    <defs id="defs5608" />
                                    <g id="Document" font-size="16" transform="matrix(1,0,0,-1,-0.001,0.012)" style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000">
                                        <g id="Spread" transform="translate(0,-105.975)">
                                            <g id="Layer 1">
                                                <g id="Group" stroke-miterlimit="79.8403193612775" style="fill:#666666;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677">
                                                    <path d="M 0.001,-0.01 V 105.987 H 105.369 V -0.01 Z m 100.982,4.386 v 97.225 H 4.387 V 4.376 Z m 11.375,-4.389 V 105.984 H 161.55 V -0.013 Z m 44.806,4.386 v 97.225 h -40.42 V 4.373 Z"
                                                        id="path5610" inkscape:connector-curvature="0" style="marker-start:none;marker-end:none" />
                                                </g>
                                            </g>
                                        </g>
                                    </g>
                                </svg>
                                <svg style="display: none" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.549pt" height="106pt"
                                    viewBox="0 0 161.54899 106" id="svg5616" sodipodi:docname="2col-1col.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.0 r15299">
                                    <metadata id="metadata5620">
                                        <rdf:RDF>
                                            <cc:Work rdf:about="">
                                                <dc:format>image/svg+xml</dc:format>
                                                <dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
                                                <dc:title></dc:title>
                                            </cc:Work>
                                        </rdf:RDF>
                                    </metadata>
                                    <sodipodi:namedview pagecolor="#ffffff" bordercolor="#666666" borderopacity="1" objecttolerance="10" gridtolerance="10" guidetolerance="10"
                                        inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="745" id="namedview5618"
                                        showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="1.6702053"
                                        inkscape:cx="107.7" inkscape:cy="70.65" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1" inkscape:current-layer="svg5616"
                                    />
                                    <defs id="defs5608" />
                                    <g id="Document" font-size="16" transform="matrix(1,0,0,-1,-0.001,0.012)" style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000">
                                        <g id="Spread" transform="translate(0,-105.975)">
                                            <g id="Layer 1">
                                                <g id="Group" stroke-miterlimit="79.8403193612775" style="fill:#0460ad;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677">
                                                    <path d="M 0.001,-0.01 V 105.987 H 105.369 V -0.01 Z m 100.982,4.386 v 97.225 H 4.387 V 4.376 Z m 11.375,-4.389 V 105.984 H 161.55 V -0.013 Z m 44.806,4.386 v 97.225 h -40.42 V 4.373 Z"
                                                        id="path5610" inkscape:connector-curvature="0" style="marker-start:none;marker-end:none" />
                                                </g>
                                            </g>
                                        </g>
                                    </g>
                                </svg>
                            </span>
                            <span class="img_svg" on-click="selctImage3">
                                <svg style="display: inline" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.55pt" height="106pt"
                                    viewBox="0 0 161.55 106" id="svg4493" sodipodi:docname="1col-2col.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.0 r15299">
                                    <metadata id="metadata4497">
                                        <rdf:RDF>
                                            <cc:Work rdf:about="">
                                                <dc:format>image/svg+xml</dc:format>
                                                <dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
                                                <dc:title></dc:title>
                                            </cc:Work>
                                        </rdf:RDF>
                                    </metadata>
                                    <sodipodi:namedview pagecolor="#ffffff" bordercolor="#666666" borderopacity="1" objecttolerance="10" gridtolerance="10" guidetolerance="10"
                                        inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="745" id="namedview4495"
                                        showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="1.4142136"
                                        inkscape:cx="33.21505" inkscape:cy="17.322511" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1"
                                        inkscape:current-layer="svg4493" />
                                    <defs id="defs4485" />
                                    <g id="Document" font-size="16" transform="matrix(1,0,0,-1,0,0.012)" style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000">
                                        <g id="Spread" transform="translate(0,-105.975)">
                                            <g id="Layer 1">
                                                <g id="Group" stroke-miterlimit="79.8403193612775" style="fill:#666666;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677">
                                                    <path d="M 56.182,-0.01 V 105.987 H 161.55 V -0.01 Z m 100.982,4.386 v 97.225 H 60.568 V 4.376 Z M 0,-0.013 V 105.984 H 49.193 V -0.013 Z m 44.807,4.386 v 97.225 H 4.386 V 4.373 Z"
                                                        id="path4487" inkscape:connector-curvature="0" style="marker-start:none;marker-end:none" />
                                                </g>
                                            </g>
                                        </g>
                                    </g>
                                </svg>
                                <svg style="display: none" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.55pt" height="106pt"
                                    viewBox="0 0 161.55 106" id="svg4493" sodipodi:docname="1col-2col.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.0 r15299">
                                    <metadata id="metadata4497">
                                        <rdf:RDF>
                                            <cc:Work rdf:about="">
                                                <dc:format>image/svg+xml</dc:format>
                                                <dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
                                                <dc:title></dc:title>
                                            </cc:Work>
                                        </rdf:RDF>
                                    </metadata>
                                    <sodipodi:namedview pagecolor="#ffffff" bordercolor="#666666" borderopacity="1" objecttolerance="10" gridtolerance="10" guidetolerance="10"
                                        inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="745" id="namedview4495"
                                        showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="1.4142136"
                                        inkscape:cx="33.21505" inkscape:cy="17.322511" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1"
                                        inkscape:current-layer="svg4493" />
                                    <defs id="defs4485" />
                                    <g id="Document" font-size="16" transform="matrix(1,0,0,-1,0,0.012)" style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000">
                                        <g id="Spread" transform="translate(0,-105.975)">
                                            <g id="Layer 1">
                                                <g id="Group" stroke-miterlimit="79.8403193612775" style="fill:#0460ad;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677">
                                                    <path d="M 56.182,-0.01 V 105.987 H 161.55 V -0.01 Z m 100.982,4.386 v 97.225 H 60.568 V 4.376 Z M 0,-0.013 V 105.984 H 49.193 V -0.013 Z m 44.807,4.386 v 97.225 H 4.386 V 4.373 Z"
                                                        id="path4487" inkscape:connector-curvature="0" style="marker-start:none;marker-end:none" />
                                                </g>
                                            </g>
                                        </g>
                                    </g>
                                </svg>
                            </span>
                            <span class="img_svg" on-click="selctImage4">
                                <svg style="display: inline" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.076pt" height="105.997pt"
                                    viewBox="0 0 161.076 105.997" id="svg6732" sodipodi:docname="full.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.0 r15299">
                                    <metadata id="metadata6736">
                                        <rdf:RDF>
                                            <cc:Work rdf:about="">
                                                <dc:format>image/svg+xml</dc:format>
                                                <dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
                                                <dc:title></dc:title>
                                            </cc:Work>
                                        </rdf:RDF>
                                    </metadata>
                                    <sodipodi:namedview pagecolor="#ffffff" bordercolor="#666666" borderopacity="1" objecttolerance="10" gridtolerance="10" guidetolerance="10"
                                        inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="745" id="namedview6734"
                                        showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="1.6702053"
                                        inkscape:cx="107.4" inkscape:cy="70.649999" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1"
                                        inkscape:current-layer="svg6732" />
                                    <defs id="defs6725" />
                                    <g id="Document" font-size="16" transform="matrix(1,0,0,-1,-0.012,0.011)" style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000">
                                        <g id="Spread" transform="translate(0,-105.975)">
                                            <g id="Layer 1">
                                                <path d="M 0.012,-0.011 V 105.986 H 161.088 V -0.011 Z m 156.69,4.386 V 101.6 H 4.398 V 4.375 Z" stroke-miterlimit="79.8403193612775"
                                                    id="path6727" inkscape:connector-curvature="0" style="fill:#666666;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
                                                />
                                            </g>
                                        </g>
                                    </g>
                                </svg>
                                <svg style="display: none" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
                                    xmlns:svg="http://www.w3.org/2000/svg" xmlns="http://www.w3.org/2000/svg" xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
                                    xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape" version="1.1" overflow="visible" width="161.076pt" height="105.997pt"
                                    viewBox="0 0 161.076 105.997" id="svg6732" sodipodi:docname="full.svg" style="overflow:visible;fill-rule:evenodd;stroke-width:0.50099999;stroke-linejoin:bevel"
                                    inkscape:version="0.92.0 r15299">
                                    <metadata id="metadata6736">
                                        <rdf:RDF>
                                            <cc:Work rdf:about="">
                                                <dc:format>image/svg+xml</dc:format>
                                                <dc:type rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
                                                <dc:title></dc:title>
                                            </cc:Work>
                                        </rdf:RDF>
                                    </metadata>
                                    <sodipodi:namedview pagecolor="#ffffff" bordercolor="#666666" borderopacity="1" objecttolerance="10" gridtolerance="10" guidetolerance="10"
                                        inkscape:pageopacity="0" inkscape:pageshadow="2" inkscape:window-width="1366" inkscape:window-height="745" id="namedview6734"
                                        showgrid="false" fit-margin-top="0" fit-margin-left="0" fit-margin-right="0" fit-margin-bottom="0" inkscape:zoom="1.6702053"
                                        inkscape:cx="107.4" inkscape:cy="70.649999" inkscape:window-x="-8" inkscape:window-y="-8" inkscape:window-maximized="1"
                                        inkscape:current-layer="svg6732" />
                                    <defs id="defs6725" />
                                    <g id="Document" font-size="16" transform="matrix(1,0,0,-1,-0.012,0.011)" style="font-size:16px;font-family:'Times New Roman';fill:none;stroke:#000000">
                                        <g id="Spread" transform="translate(0,-105.975)">
                                            <g id="Layer 1">
                                                <path d="M 0.012,-0.011 V 105.986 H 161.088 V -0.011 Z m 156.69,4.386 V 101.6 H 4.398 V 4.375 Z" stroke-miterlimit="79.8403193612775"
                                                    id="path6727" inkscape:connector-curvature="0" style="fill:#0460ad;fill-rule:evenodd;stroke:none;stroke-width:0.5;stroke-miterlimit:79.84031677;marker-start:none;marker-end:none"
                                                />
                                            </g>
                                        </g>
                                    </g>
                                </svg>
                            </span>
                        </div> -->
                    </div>
                </div>
            </div>

            <!-- <div class="form-group">
                <label for="exemplar" class="col-md-2 control-label">Exemplar
                    &nbsp;
                </label>
                <div class="col-md-10">
                    <select class="form-control" data-role="select2" id="exemplar" multiple name="exemplar">
                        <option value="1">titulo1</option>
                        <option value="2">titulo2</option>
                        <option value="3">titulo3</option>
                    </select>
                </div>
            </div> -->

            <div class="row">
                <div class="col-xs-6 col-sm-5">
                    <div class="form-group">
                        <label>
                            Team:
                        </label>
                        <select class="form-control" multiple>
                            <option>Iron</option>
                            <option>Captan</option>
                            <option>Lind</option>
                            <option>Kelvin</option>
                        </select>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-xs-6 col-sm-5">
                    <div class="form-group">
                        <label>
                            Team Members:
                        </label>
                        <select class="form-control" multiple>
                        </select>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-xs-6 col-sm-5">
                    <button class="btn btn-primary">Create</button>
                    <button class="btn btn-primary">Cancel</button>    
                </div>
            </div>
        </div>
    </form>
        <!--  -->
</template>

<script>
export default {
  
}
</script>

<style scoped>

</style>
