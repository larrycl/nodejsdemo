# nodejsdemo
# Use this code snippet
var os = require('os');
  var hostname = os.hostname();
  var ip = require('ip');  // npm install ip

  $result = "Hello World!" + "<p>This is host " + hostname + " on " + ip.address();
  res.send($result);
  
