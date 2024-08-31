const ssid = $network.wifi.ssid;
const targetSSID = "ZSYZYD_5G_Game";
const domain = "zhouhuishine.mycloudnas.com";
const ip = "192.168.71.6";  // 替换为你想要映射的IP地址

if (ssid === targetSSID) {
    $surge.setDnsResult(domain, ip);
    console.log(`Mapped ${domain} to ${ip} on ${ssid}`);
} else {
    $surge.setDnsResult(domain, null);
    console.log(`Removed mapping for ${domain} on ${ssid}`);
}

$done();
