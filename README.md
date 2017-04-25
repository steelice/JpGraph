# Librairie JpGraph IK

## Version 4.0.3
* Fork du projet JpGraph : https://github.com/ztec/JpGraph
* Compatible PHP7 

## Installation

fichier : composer.json

    {
        "repositories": [
            [...],
            {
                "type": "git",
                "url": "https://github.com/yieloo/JpGraph.git"
            }
        ],
        "require": {
            [...]
            "yieloo/JpGraph" : "4.0.3"
        }
    }

JpGraph from http://jpgraph.net/
======
This is a port for Composer users to use JpGraph as a Vendor library

use JpGraph\JpGraph::load(); and JpGraph\JpGraph::module('moduleName'); to load required modules
