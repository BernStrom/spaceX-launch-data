<div align="center">
    <img alt="SpaceX Logo" src="./images/spacex.jpg" />
</div>

<h1 align="center">
    SpaceX Launch Data
</h1>

<h6 align="center">
    Launch data from an open-source <a href="https://github.com/r-spacex/SpaceX-API">SpaceX API</a> by the subreddit community <a href="https://www.reddit.com/r/spacex/">r/SpaceX</a>
</h6>

## About
A mini-program built with Deno that returns a set of ![SpaceX]("https://www.spacex.com/" "SpaceX") launch data in a JSON string using the ![log]("https://deno.land/std@0.90.0/log" "Log module") module from Deno's standard library. Results of the launch data are set to flight numbers, mission name, rocket name and customer(s) name.

## Installation

_**Note: Before running the program, please ensure you have Deno installed on your machine.**_

1. Follow the installation instructions on the Deno offical website: https://deno.land/
2. In your terminal, run: `deno run --allow-net=api.spacexdata.com mod.ts`
3. You should see the program return back the launch data in a JSON string format:

        INFO {"flightNumber":103,"mission":"Starlink-12 (v1.0)","rocket":"Falcon 9","customers":["SpaceX"]}
        INFO {"flightNumber":104,"mission":"Starlink-13 (v1.0)","rocket":"Falcon 9","customers":["SpaceX"]}
        INFO {"flightNumber":105,"mission":"Starlink-14 (v1.0)","rocket":"Falcon 9","customers":["SpaceX"]}
        INFO {"flightNumber":106,"mission":"GPS III SV04 (Sacagawea)","rocket":"Falcon 9","customers":["United States Space Force"]}
        INFO {"flightNumber":107,"mission":"Crew-1","rocket":"Falcon 9","customers":["NASA (CCtCap)"]}
        INFO {"flightNumber":108,"mission":"Sentinel-6 Michael Freilich","rocket":"Falcon 9","customers":["NASA"]}
        INFO {"flightNumber":109,"mission":"Starlink-15 (v1.0)","rocket":"Falcon 9","customers":["SpaceX"]}
        INFO {"flightNumber":110,"mission":"CRS-21","rocket":"Falcon 9","customers":["NASA (CRS)"]}
        INFO {"flightNumber":110,"mission":"SXM-7","rocket":"Falcon 9","customers":["SiriusXM"]}
        INFO Downloaded data for 110 SpaceX launches 💫

## :memo: License [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project is licensed under the terms of the MIT license. For more information, please refer to the license [documentation](LICENSE.md).

## :warning: Disclaimer
This program uses an unofficial API that bares no official association, affiliation, authorization or endorsement of any kind to Space Exploration Technologies Corp (SpaceX) or any of its subsidiaries or its affiliates.

The contents of these pages are provided as an information guide only. While every effort is made in preparing the material for publication, no responsibility is accepted by or on behalf of the owner(s) for any errors, omissions or misleading statements on these pages or any site to which these pages connect. Although every effort is made to ensure the reliability of listed sites this cannot be taken as an endorsement of these sites.