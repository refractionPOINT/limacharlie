<img src="https://storage.googleapis.com/lc-edu/marketing-assets/github-banner.jpeg"
     alt="LimaCharlie.io Logo"
     style="width: 100%; padding-bottom: 40px;" />
     
<p>The open source version of [LimaCharlie](https://limacharlie.io) has been turned into a fully-hosted commercial offering that includes a [free tier](https://app.limacharlie.io/signup).</p>

<p>LimaCharlie provides information security tools and infrastructure designed for massive scale. The platform supplies all the tools to run an MSSP or SOC as well as providing API’s that allow users to build and monetize their own products.</p>

<p>Developer documentation can be found <a href="https://doc.limacharlie.io/docs/documentation/docs/index.md" target="_blank">here</a>.</p>
<p></p>

<p>Practical guides to getting things done can be found in the LimaCharlie Help Center <a href="https://help.limacharlie.io/en/" target="_blank">here</a>.

<p>The REST API Documentation can be found <a href="https://doc.limacharlie.io/docs/api/container/static/swagger/v1/swagger.json" target="_blank">here</a>.</p>

## Quickstart
<p>To skip all of the details and get set up with endpoint detection and response capability you can follow our <a href="https://doc.limacharlie.io/docs/documentation/ZG9jOjEwMjE0Mg-getting-started" target="_blank">Getting Started guide</a> or take the in-depth <a href="https://edu.limacharlie.io/courses/quickstart" target="_blank">Quickstart e-learning course</a>.</p>

## Feedback & Feature Requests

<p>If have feedback or would like to make a feature request please fill out the form <a href="https://www.limacharlie.io/user-ticket" target="_blank">here</a>.</p>

<hr>

# <span style="color:#3889c7">Products</span>

## <span style="color:#3889c7">Endpoint Detection & Response</span>

<p>LimaCharlie provides a true-real-time Endpoint Detection & Response (EDR) capability. Verbose telemetry is streamed from the endpoint sensor to the cloud in real-time over a semi-persistent TLS connection. Response actions are taken on the endpoint within 100ms of the triggering action or behaviour.</p>

<p>Endpoint telemetry is ingested and analyzed in-flight by the Detection & Response Engine. Telemetry can be tested against thousands of rules without impacting performance.</p>

<p>LimaCharlie’s EDR sensor generates telemetry for a wide variety of <a href="https://doc.limacharlie.io/docs/documentation/ZG9jOjE5MzExMDQ-events">event data</a> that is delivered in a common JSON format.</p>

<h3>Detection</h3>

<p>A versatile YAML-based detection syntax can be used to create detections for highly sophisticated behaviour, including the ability to track state and build multi-step detection logic that runs at wire speed.</p> 

<p>This same detection syntax can also be used to easily achieve the following:</p>

<ul>
    <li>Run Sigma rules</li>
    <li>Run continuous YARA scans without impacting performance</li>
    <li>Monitor file and registeries</li>
    <li>Leverage threat feeds or lookups</li>
    <li>Check hashes against VirusTotal</li>
    <li>Create rules against telemetry from Windows Defender</li>
    <li>Check domains using Levenshtein distance to detect spear phishing</li>
</ul>

A repository of sample detection rules can be found in this repository: <a href="https://github.com/refractionPOINT/rules">Sample Rule Set</a>.

The full open source Sigma ruleset (which can be enabled on deployments at the click of a button) can be found here: <a href="https://github.com/refractionPOINT/sigma">Sigma Rule Set</a>

<h3>Response</h3>

<p>When a detection is triggered a response action is initiated. A response can take an action on the endpoint or be used to automate many aspects of security operations. Response actions can include:</p>

<ul>
    <li>Kill a process or process tree</li>
    <li>Trigger memory dumps</li>
    <li>Issue an alert to a wide variety of destination types including the web application, any webhook, SMTP, PagerDuty, Kafka, SCP and more</li>
    <li>Initiate full PCAP capture from the network without impacting performance</li>
    <li>Trigger log ingestion and analysis</li>
    <li>Deploy and run any executable on endpoint such as patches or custom scripts</li>
</ul>

<p>Documentation on LimaCharlie's EDR/XDR capability can be found <a href="https://doc.limacharlie.io/docs/documentation/docs/lc-edr.md">here</a></p>

## <span style="color:#3889c7">Software Defined Networking</span>

<p>LimaCharlie Net is a Secure Access Service Edge (SASE) that rolls SD-WAN into a cloud service. It changes the way that secure remote access is delivered. It is much more than a virtual private network and can be established with the click of a button. It is a micro-segmentable network that can capture full or partial PCAP files entirely in the cloud without impacting users. These captured files can also be analyzed with the <a href="https://zeek.org/" target="_blank">Zeek Network Monitoring Tool</a> and have detection rules written against them.</p>

<p>LimaCharlie Net is available for Windows, MacOS, Linux, iOS, Android and Chrome OS.</p>

<p>Documentation on LimaCharlie Net can be found <a href="https://doc.limacharlie.io/docs/documentation/docs/lc-net.md">here</a></p>

## <span style="color:#3889c7">Log & Artifact Ingestion</span>

<p>LimaCharlie has the ability to ingest and process a large and ever growing list of file types and telemetry.</p>  

<p>By leveraging this capability, LimaCharlie users can ingest and then write detection and response rules for just about anything out there.</p>

<p>If there is something you want to monitor that we do not yet support feel free to let us know. We frequently add support for new formats, and the turnaround is typically measured in days.</p>

<p>Everything can be automated via the full-featured API or manually through the LimaCharlie web application.</p>

<p>Currently supported file types and telemetry:</p>
<ul>
    <li>Plain text logs, like syslog for example</li>
    <li>Windows Event Logs in real-time</li>
    <li>PCAPs which can then be processed using the Zeek network monitoring tool</li>
    <li>Windows Prefetch files</li>
    <li>Windows PE (executables) files</li>
    <li>Full memory dumps automated across the entire fleet</li>
    <li>Generic JSON</li>
    <li>OLE (MS Word, Excel etc)</li>
    <li>Windows MFT CSV Listing</li>
    <li>Apple Binary/XML plists</li>
</ul>

<p>Documentation on Log & Artifact Ingestion can be found <a href="https://doc.limacharlie.io/docs/documentation/docs/lc-artifact_ingestion.md">here</a></p>

# <span style="color:#3889c7">Education</span> 

<table style="width: 100%;">
    <tr>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">General Overview</h2>
            <p>A high-level overview of the LimaCharlie platform. It explains the architecture and various components of the platform at a high level.</p>
            <p><a href="https://edu.limacharlie.io/courses/general-overview" target="_blank">E-Learning Course</a></p>
        </td>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">Quickstart</h2>
            <p>The quickest way to get going. This course walks you through setting up your first DR rule, adding a threat feed, monitoring string distance and configuring email alerts.</p>
            <p><a href="" target="_blank">E-Learning Course</a></p>
            <p><a href="" target="_blank">Documentation</a></p>
        </td>
    </tr>
    <tr>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">Basic Detection & Response</h2>
            <p>An introduction to the principles of detection and response with an examination of basic DR rules.</p>
            <p><a href="https://edu.limacharlie.io/courses/basic-detection-response" target="_blank">E-Learning Course</a></p>
            <p><a href="https://www.youtube.com/playlist?list=PLO8_Yc4h5cIoreJ9ELkuOAX48Z76uiobI" target="_blank">YouTube Playlist</a></p>
        </td>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">Advanced Detection & Response</h2>
            <p>A brief review of basic DR followed by an examination of Artifact Events, False Positive Rules, Variables, Lookups and Stateful Rules.</p>
            <p><a href="https://edu.limacharlie.io/courses/advanced-detection-response" target="_blank">E-Learning Course</a></p>
            <p><a href="https://www.youtube.com/playlist?list=PLO8_Yc4h5cIrPSK6ws1O0ZwydgN2gR1Bb" target="_blank">YouTube Playlist</a></p>
        </td>
    </tr>
    <tr>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">Setting up an MSSP</h2>
            <p>This course outlines best practices for the most efficient use of LimaCharlie at scale. This structure is ideal for a Managed Security Service Provider (MSSP) or Security Operations Center (SOC) that is managing multiple organizations.</p>
            <p><a href="https://edu.limacharlie.io/courses/setting-up-an-mssp" target="_blank">E-Learning Course</a></p>
            <p><a href="https://www.youtube.com/playlist?list=PLO8_Yc4h5cIouf3f8192rA3UqV1xvCqr2" target="_blank">YouTube Playlist</a></p>
        </td>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">Using the CLI & SDK</h2>
            <p>With the CLI users can search across their entire fleet, search over historical data, replicate orgs, run spot checks on endpoints, push logs for ingestion. With the SDK users can capture data from the firehose or spout, and much much more.</p>
            <p><a href="https://edu.limacharlie.io/courses/using-the-cli-sdk" target="_blank">E-Learning Course</a></p>
            <p><a href="https://www.youtube.com/playlist?list=PLO8_Yc4h5cIp43_ZqQfFf7HPRPGo5QleZ" target="_blank">YouTube Playlist</a></p>
        </td>
    </tr>
    <tr>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">Monitor Windows Event Logs in Real-Time</h2>
            <p>In this course you will learn about LimaCharlie’s powerful ability to capture and analyze Windows Event Logs (WEL) in real-time. Ingested WEL are indexed along common indicators of compromise (IoC’s) and run through the Detection & Response engine.</p>
            <p><a href="https://edu.limacharlie.io/courses/monitor-windows-event-logs-in-real-time" target="_blank">E-Learning Course</a></p>
            <p><a href="https://www.youtube.com/playlist?list=PLO8_Yc4h5cIrLAZ8i6uO-NkUO9zsOZz7O" target="_blank">YouTube Playlist</a></p>
        </td>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">Zeek Network Monitoring</h2>
            <p>In this course LimaCharlie founder, Maxime Lamothe-Brassard walks through how users can leverage the agent to do PCAP capture on the network. Once the PCAPS are captured they can be re-ingested and processed by the Zeek Network Monitoring Tool.</p>
            <p><a href="https://edu.limacharlie.io/courses/zeek-network-monitoring" target="_blank">E-Learning Course</a></p>
            <p><a href="https://www.youtube.com/playlist?list=PLO8_Yc4h5cIrDNYBh2Q80-USSY5duXTqQ" target="_blank">YouTube Playlist</a></p>
        </td>
    </tr>
    <tr>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">Ingesting Artifacts (Windows Event Logs, PCAPS, pfSense, Syslog & more)</h2>
            LimaCharlie can ingest almost any form of telemetry or logs and run detection rules against them. Windows Event Logs, PCAPS, pfSense, Syslog and many more with new formats being added constantly. Learn about ingesting and analyzing artifacts.</p>
            <p><a href="https://edu.limacharlie.io/courses/ingesting-artifacts-windows-event-logs-pcaps-pfsense-syslog-more" target="_blank">E-Learning Course</a></p>
            <p><a href="https://www.youtube.com/playlist?list=PLO8_Yc4h5cIrTTgk638zQbogEe0SCZkOY" target="_blank">YouTube Playlist</a></p>
        </td>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">Secure Access Service Edge (SASE)</h2>
            <p>LimaCharlie Net is a Zero Trust solution that can create secure connections to internal resources based on the identity of the device regardless of the client location. Simple policies, mass provisioning, PCAP capture and analysis and much more!</p>
            <p><a href="https://edu.limacharlie.io/courses/secure-access-service-edge" target="_blank">E-Learning Course</a></p>
            <p><a href="https://www.youtube.com/playlist?list=PLO8_Yc4h5cIrQNvaFzsZLRwt5oI5M1w1s" target="_blank">YouTube Playlist</a></p>
        </td>
    </tr>
    <tr>
        <td style="width: 45%; vertical-align: top;">
            <h2 style="color: #3b8452;">The Add-on Marketplace</h2>
            <p>LimaCharlie offers pre-configured capabilities and services that can be enabled at the click of a button through the Add-on Marketplace. Learn what types of capabilities and services are available and how you can make your own additions.</p>
            <p><a href="https://edu.limacharlie.io/courses/exploring-the-add-on-marketplace" target="_blank">E-Learning Course</a></p>
            <p><a href="https://www.youtube.com/playlist?list=PLO8_Yc4h5cIrPOuJ4NM_NFMVER0DUyGFi" target="_blank">YouTube Playlist</a></p>
        </td>
        <td style="width: 45%; vertical-align: top;">
        </td>
    </tr>
</table>
˛
