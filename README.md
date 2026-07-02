<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN"
"http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>

    <key>PayloadType</key>
    <string>Configuration</string>

    <key>PayloadVersion</key>
    <integer>1</integer>

    <key>PayloadIdentifier</key>
    <string>com.example.gamingdns</string>

    <key>PayloadUUID</key>
    <string>3A7D0F7C-9A6F-4F8B-9B26-5A7E2E4C1234</string>

    <key>PayloadDisplayName</key>
    <string>Gaming DNS</string>

    <key>PayloadContent</key>
    <array>
        <dict>

            <key>PayloadType</key>
            <string>com.apple.dnsSettings.managed</string>

            <key>PayloadVersion</key>
            <integer>1</integer>

            <key>PayloadIdentifier</key>
            <string>com.example.gamingdns.dns</string>

            <key>PayloadUUID</key>
            <string>7B62A4E2-5E2B-41B8-8D6F-8C91F2A71234</string>

            <key>PayloadDisplayName</key>
            <string>Cloudflare DNS</string>

            <key>DNSSettings</key>
            <dict>
                <key>DNSProtocol</key>
                <string>HTTPS</string>

                <key>ServerURL</key>
                <string>https://cloudflare-dns.com/dns-query</string>
            </dict>

        </dict>
    </array>

</dict>
</plist>
