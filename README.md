# Fastly nodejs Client


## Works like this

    var fastly = require("fastly");

    var api = new fastly.FastlyAPI();	
    api.authenticateByKey("123");
    api.purgeUrl("andyhume.net", "/about");