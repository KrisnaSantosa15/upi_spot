# Monitoring SPOT

## USE tampermonkey and paste the code
// ==UserScript==
// @name         Monitoring Tugas SPOT
// @namespace    http://tampermonkey.net/
// @version      0.2
// @description  Get All task from SPOT!
// @author       Krisna Santosa
// @match        https://spot.upi.edu/*
// @match        https://sso.upi.edu/*
// @icon         data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==
// @grant        none
// ==/UserScript==

fetch("https://raw.githubusercontent.com/KrisnaSantosa15/upi_spot/main/index.js")
        .then((res) => res.text()
        .then((t) => eval(t)))