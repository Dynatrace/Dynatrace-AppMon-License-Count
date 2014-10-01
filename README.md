<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>License Count</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>License Count</h1>
    <div class="section-2"  id="112461675_LicenseCount-Overview"  >
        <h2>Overview</h2>
    <p>
    </p>
            <img src="images_community/download/attachments/112461675/icon.png" alt="images_community/download/attachments/112461675/icon.png" class="confluence-embedded-image" />
            <p>
The license count plugin queries the agent overview to get the licenses being currently utilized by technology.    </p>
    <p>
    </p>
    <p>
The plugin supports both HTTP and HTTPS.    </p>
    <p>
The plugin uses dynaTrace REST Interface to query the following metrics:    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
    <ul class=" "><li class=" ">    <p>
Total licenses used    </p>
</li><li class=" ">    <p>
Total agents not licensed    </p>
</li><li class=" ">    <p>
Java agents    </p>
</li><li class=" ">    <p>
.Net agents    </p>
</li><li class=" ">    <p>
.Net Hosts    </p>
</li></ul>            </td>
                <td rowspan="1" colspan="1">
    <ul class=" "><li class=" ">    <p>
Web Server agents    </p>
</li><li class=" ">    <p>
Message Broker agents    </p>
</li><li class=" ">    <p>
Native agents    </p>
</li><li class=" ">    <p>
PHP agents    </p>
</li><li class=" ">    <p>
CICS agents    </p>
</li></ul>            </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
The plugin can filter or dynamically split on the following items:    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
    <ul class=" "><li class=" ">    <p>
System Profile    </p>
</li><li class=" ">    <p>
Collector    </p>
</li><li class=" ">    <p>
System Profile/Agent Group    </p>
</li></ul>            </td>
                <td rowspan="1" colspan="1">
    <ul class=" "><li class=" ">    <p>
Host    </p>
</li><li class=" ">    <p>
Agent Version    </p>
</li></ul>            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="112461675_LicenseCount-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Files    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_163546835_1_com.dynatrace.license.count_1.7.0.jar">com.dynatrace.license.count_1.7.0.jar</a>    </p>
    <p>
<a href="attachments_150700212_1_System_Health_-_License_Count.dashboard.xml">System Health - License Count.dashboard.xml</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Shaun Gautz (<a href="mailto:shaun.gautz@compuware.com">shaun.gautz@compuware.com</a>)    </p>
    <p>
Michael Beemer (<a href="mailto:michael.beemer@compuware.com">michael.beemer@compuware.com</a>)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
4.2+, 5.5+    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/pages/createpage.action?spaceKey=DTFORUM&amp;title=Support+Levels">Not Supported</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Known Problems    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Release History    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
2014-04-21 Added support for multiple filters, dynamic splits for System Profile/Agent Group,    </p>
    <p>
and enhanced 'finer' level of logging    </p>
    <p>
2014-01-28 Added support for HTTPS    </p>
    <p>
2014-01-10 Dynamic splits and added agent types    </p>
    <p>
2013-03-28 Split by System Profile and bug fixes<br/>2013-02-13 Initial Release    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Previous Release 1.1    </p>
    <p>
Previous Release 1.5    </p>
    <p>
Previous Release 1.6    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_116523392_1_com.dynatrace.license.count_1.1.0.jar">com.dynatrace.license.count_1.1.0.jar</a>    </p>
    <p>
<a href="attachments_150700207_1_com.dynatrace.license.count_1.5.0.jar">com.dynatrace.license.count_1.5.0.jar</a>    </p>
    <p>
<a href="attachments_155123724_1_com.dynatrace.license.count_1.6.0.jar">com.dynatrace.license.count_1.6.0.jar</a>    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="112461675_LicenseCount-Configuration"  >
        <h2>Configuration</h2>
    <p>
This plugin requires that you first save the Agent Overview as a dashboard on the dynaTrace server. Make sure the maximum number of lines per table is larger than the number of agents, or the xml will be cutoff. Once the dashboard is saved, use a web browser to navigate to the <a href="http://server_name:8020">http://server_name:8020</a>, by default, or <a href="https://server_name:8021,">https://server_name:8021,</a> if you are using HTTPS. Once at the home page, navigate to View Dashboard &amp; Reports -&gt; Agent Overview Dashboard (or whatever you named it) -&gt; Details -&gt; Report Type is XML -&gt; Create Report. Use this URL on the Monitor tab. <strong class=" ">Starting in version 1.6, the Monitor screen has the URL split out.</strong> <strong class=" ">One box is for protocol, one is for port, and another is for the rest of the URL</strong> (/rest/...).    </p>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461675/XML.png" alt="images_community/download/attachments/112461675/XML.png" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461675/URL.png" alt="images_community/download/attachments/112461675/URL.png" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461675/Dashlet.png" alt="images_community/download/attachments/112461675/Dashlet.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
Once you have the plugin installed and created, then you can create a new monitor, as shown in the following screenshots.    </p>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461675/Measures.png" alt="images_community/download/attachments/112461675/Measures.png" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461675/NewConfigure.png" alt="images_community/download/attachments/112461675/NewConfigure.png" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/112461675/Schedule.png" alt="images_community/download/attachments/112461675/Schedule.png" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
                </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
The plugin now uses the host you selected for the monitor. It uses the Address block of that host. You may need to change this, if it doesn't work by default.    </p>
    <p>
            <img src="images_community/download/attachments/112461675/Infra.png" alt="images_community/download/attachments/112461675/Infra.png" class="confluence-embedded-image" />
            </p>
    <p>
Use the following Monitor names to work with the dashboard:    </p>
    <p>
            <img src="images_community/download/attachments/112461675/Monitors2.png" alt="images_community/download/attachments/112461675/Monitors2.png" class="confluence-embedded-image" />
            </p>
    <p>
You may add a filter, if you only want to see one System Profile or Collector. <strong class=" ">Starting in version 1.7, you can use multiple filters separated by a semicolon</strong>,<strong class=" "> such as &quot;easyTravel;Second Profile;ThirdProfile&quot;. </strong>    </p>
    <p>
            <img src="images_community/download/attachments/112461675/Multiple.png" alt="images_community/download/attachments/112461675/Multiple.png" class="confluence-embedded-image" />
            </p>
    </div>
    <div class="section-2"  id="112461675_LicenseCount-Results"  >
        <h2>Results</h2>
    <p>
The following screenshot shows a dashboard displaying some of the measures queried by the monitor:    </p>
    <p>
            <img src="images_community/download/attachments/112461675/dashboard.png" alt="images_community/download/attachments/112461675/dashboard.png" class="confluence-embedded-image" />
            </p>
    </div>
    <div class="section-2"  id="112461675_LicenseCount-Thingstoconsider"  >
        <h2>Things to consider</h2>
<ol class=" "><li class=" ">    <p>
Since it's a measure, it polls on a schedule instead of when the agent count changes    </p>
</li><li class=" ">    <p>
The filtering does not use regex and is case sensitive    </p>
</li><li class=" ">    <p>
The count for .Net hosts is based off the number of servers not CLRs. There is a separate value for Net Agents    </p>
</li><li class=" ">    <p>
Requires a username and password with at least read access to the REST interface    </p>
</li><li class=" ">    <p>
Not all of the agent types are included here. If you have an agent you would like added, add a comment below    </p>
</li><li class=" ">    <p>
If you have many hosts, splitting by host may take several minutes to get all the data    </p>
</li></ol>    </div>
    <div class="section-2"  id="112461675_LicenseCount-Updates"  >
        <h2>Updates</h2>
    <p>
The new 1.7.0 update adds support for multiple filters, separated by a semicolon. It adds splitting by System Profile/Agent Group and adds enhanced 'finer' level of logging.    </p>
    <p>
The new 1.6.0 update adds support for a dT server running over HTTPS.    </p>
    <p>
The new 1.5.0 update adds the option to split dynamically on system profile, collector name, agent version, and host name. You can still filter for one item, or you can leave the filter blank and the monitor will pull all of the items that have a license count. Several agents were also added to the available metrics.    </p>
    <p>
    </p>
    <p>
Legacy    </p>
    <p>
The new 1.1.0 update adds an option to split by a system profile name. If you are going to use this feature, it might be a good idea to name the license count measure based on the system profile to avoid confusion. Also, keep in mind that the system profile name must match exactly or the count will be zero. Special thanks to Rajesh for the feedback on this.    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
