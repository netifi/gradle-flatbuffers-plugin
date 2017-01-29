gradle-flatbuffers-plugin
===
[![Build Status](https://travis-ci.org/gregwhitaker/gradle-flatbuffers-plugin.svg?branch=master)](https://travis-ci.org/gregwhitaker/gradle-flatbuffers-plugin)

Gradle plugin for generating code from Google [FlatBuffers](https://google.github.io/flatbuffers/) schemas.

##Requirements

This plugin requires that the FlatBuffers compiler be installed on the system.

For information on building and installing the compiler please refer to the [FlatBuffers Documentation](https://google.github.io/flatbuffers/flatbuffers_guide_building.html).

##Usage
Please see the [Gradle Plugin Portal](https://plugins.gradle.org/plugin/com.github.gregwhitaker.flatbuffers) for instructions on including this plugin in your project.

###Extension Properties
The plugin defines the following extension properties in the `flatbuffers` closure:

| Property  | Type   | Default Value | Description                                        |
|-----------|--------|---------------|----------------------------------------------------|
| flatcPath | String | flatc         | The path to the flatc compiler.           |
| language  | String | null          | The language to compile to generate FlatBuffers in.|

###Custom Task Types

##Bugs and Feedback

For bugs, questions and discussions please use the [Github Issues](https://github.com/gregwhitaker/gradle-flatbuffers-plugin/issues).

##License
Copyright 2017 Greg Whitaker

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.