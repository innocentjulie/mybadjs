# mybadjs
1：修改badjs-acceptor-master中，service中的ProjectService.js
var monitPort =  global.pjconfig.monitPort;
console.log("monitport =  "+monitPort);
monitPort放到project.json配置文件中
2:修改badjs-web-master中，service中的OfflineLogService.js，
var offlinePort =  global.pjconfig.offlinePort;
console.log("offlinePort =  "+offlinePort);
offlinePort放到project.json配置文件中
3：修改某些配置文件的端口
