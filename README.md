# chouchou

[![Build Status](https://travis-ci.org/goibibo/chouchou.png?branch=master)](https://travis-ci.org/goibibo/chouchou)

## Overview

A backend platform/service allowing rapid developing of front-end apps.

## Requirements

 - MongoDB
 - NodeJS 

## Installation

	git clone https://github.com/goibibo/chouchou.git
	npm install
	npm link

## Run
 - Update config.js with your settings.
 - Update system environment in chouchou.js
  - For development
  	var server = new Server(config.__CONFIG__.development);
  - For production
  	var server = new Server(config.__CONFIG__.production);
 - Execute
  - In PRODUCTION mode
  	node chouchou
  - In DEBUG mode
  	DEBUG=* node chouchou 

## License

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.