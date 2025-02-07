# FirebaseArduino

[![Build Status](https://travis-ci.org/firebase/firebase-arduino.svg?branch=master)](https://travis-ci.org/firebase/firebase-arduino)
[![Join the chat at https://gitter.im/googlesamples/firebase-arduino](https://badges.gitter.im/googlesamples/firebase-arduino.svg)](https://gitter.im/googlesamples/firebase-arduino?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![Documentation Status](https://readthedocs.org/projects/firebase-arduino/badge/?version=latest)](http://firebase-arduino.readthedocs.io/en/latest/?badge=latest)

## [EN-US]

This repo contains a collection of samples and an Arduino library that show how to call the [Firebase](https://www.firebase.com/) API from the [ESP8266 Arduino core](https://github.com/esp8266/Arduino).

The Arduino library is [under heavy development](https://github.com/googlesamples/firebase-arduino/issues), **experimental**, **unversioned** and its API is **not stable**.

## Samples

- [FirebaseDemo](https://github.com/googlesamples/firebase-arduino/tree/master/examples/FirebaseDemo_ESP8266) - shows the FirebaseArduino API methods.
- [FirebaseRoom](https://github.com/googlesamples/firebase-arduino/tree/master/examples/FirebaseRoom_ESP8266) - shows how to push sensor data and trigger actuator from Firebase.
- [FirebaseStream](https://github.com/googlesamples/firebase-arduino/tree/master/examples/FirebaseStream_ESP8266) - shows the FirebaseArduino streaming API.
- [FirebaseNeoPixel](https://github.com/googlesamples/firebase-arduino/tree/master/examples/FirebaseNeoPixel_ESP8266) - shows how to control an array of LEDs from a Firebase web app. 

## Documentation

- [FirebaseArduino API Reference](http://firebase-arduino.readthedocs.io/)

## Dependencies
- FirebaseArduino now depends on [ArduinoJson library](https://github.com/bblanchon/ArduinoJson) instead of containing it's own version of it. Please either use Library Manager or download specific version of the library from github. We recommend that ArduinoJson is at least version [5.13.1](https://github.com/bblanchon/ArduinoJson/tree/v5.13.1)

- ESP8266 Core SDK. We recommend using officially tagged releases and it should be at least [2.4.1](https://github.com/esp8266/Arduino/tree/2.4.1)

## Disclaimer

*This is not an official Google product*.

## [PT-BR]

Este repositório contém uma coleção de amostras e uma biblioteca do Arduino que mostra como chamar a API [Firebase](https://www.firebase.com/) para [ESP8266 Arduino Core](https://github.com/esp8266/Arduino).

A biblioteca do Arduino está em [desenvolvimento](https://github.com/googlesamples/firebase-arduino/issues), **EXPERIMENTAL**, **NÃO VERSIONADA** e a API **NÃO É ESTÁVEL**.

## Exemplos

- [FirebaseDemo](https://github.com/googlesamples/firebase-arduino/tree/master/examples/FirebaseDemo_ESP8266) - mostra os métodos da API FirebaseArduino.
- [FirebaseRoom](https://github.com/googlesamples/firebase-arduino/tree/master/examples/FirebaseRoom_ESP8266) - mostra como enviar dados e um sensor e acionar um atuador usando o Firebase.
- [FirebaseStream](https://github.com/googlesamples/firebase-arduino/tree/master/examples/FirebaseStream_ESP8266) - mostra a API de streaming do FirebaseArduino.
- [FirebaseNeoPixel](https://github.com/googlesamples/firebase-arduino/tree/master/examples/FirebaseNeoPixel_ESP8266) - mostra como controlar uma matriz de LEDs usando um aplicativo web que utiliza o Firebase.

## Documentação

- [Referência da API do FirebaseArduino](http://firebase-arduino.readthedocs.io/)

## Dependências
- O FirebaseArduino depende da [biblioteca ArduinoJson](https://github.com/bblanchon/ArduinoJson) em vez de conter sua própria versão. Por favor, use o gerenciador de bibliotecas do Arduino IDE para instalar ou faça o download da versão específica da biblioteca no github e instale manualmente. Utilize o ArduinoJson na sua versão [5.13.1](https://github.com/bblanchon/ArduinoJson/tree/v5.13.1).

- Para programar a ESP8266 no Arduino IDE instale o SDK oficial utilizando o gerenciador de placas do Arduino IDE, recomendamos a versão [2.4.1](https://github.com/esp8266/Arduino/tree/2.4.1)

## Aviso Legal

*Este não é um produto oficial do Google*.
