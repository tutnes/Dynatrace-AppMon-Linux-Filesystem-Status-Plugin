<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>Linux Filesystem Status Plugin</title>
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
                <h1>Linux Filesystem Status Plugin</h1>
    <div class="section-2"  id="73401401_LinuxFilesystemStatusPlugin-Overview"  >
        <h2>Overview</h2>
    <p>
The monitor gets the filesystem percent usage via the df -Plk command. The user credentials entered when configuring the monitor must have ssh access to the remote server you wish to monitor.    </p>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/73401401/Linux_Filesystem_Monitor.JPG" alt="images_community/download/attachments/73401401/Linux_Filesystem_Monitor.JPG" class="" />
            </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
            <img src="images_community/download/attachments/73401401/Linux_Filesystem_Monitor_Measure.JPG" alt="images_community/download/attachments/73401401/Linux_Filesystem_Monitor_Measure.JPG" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Configuration screen for Linux Filesystem Monitor    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Measures provided by Linux Filesystem Monitor    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="73401401_LinuxFilesystemStatusPlugin-PluginDetails"  >
        <h2>Plugin Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Versions    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_73335090_1_com.dynatrace.diagnostics.plugins.LinuxFilesystemStatusPlugin_1.0.1.jar">Linux Filesystem Status Plugin 1.0.1</a> (compatible with dynaTrace 3.5.2+)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Derek Abing    </p>
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
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Not Supported </a><br/>If you have any questions or suggestions for these plugins, please add a comment to this page, use our <a href="https://community.dynatrace.com/community/pages/viewpage.action?pageId=46628918">forum</a>, or drop us an email at <a href="mailto:community@dynatrace.com">community@dynatrace.com</a>!    </p>
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
2012-03-05 Initial Release    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="73401401_LinuxFilesystemStatusPlugin-ProvidedMeasures"  >
        <h2>Provided Measures</h2>
<ul class=" "><li class=" ">    <p>
<strong class=" ">PercentUsage</strong>: Returns percentage usage of specified filesystem.    </p>
</li></ul>    <p>
For further Unix monitoring measures, please refer to the documentation on    </p>
    <p>
<a href="https://community/display/DOCDT50/Unix+System+Monitoring">Unix System Monitoring</a>.    </p>
    </div>
    <div class="section-2"  id="73401401_LinuxFilesystemStatusPlugin-Configuration"  >
        <h2>Configuration</h2>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Value    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Filesystem    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Linux filesystem name.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Method    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Specify the type of Connection.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Authentication Method    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Specify the type of SSH Authentication.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Username    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
The username that is used for authorization with the host.    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Password    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
The password for the username.    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="73401401_LinuxFilesystemStatusPlugin-Installation"  >
        <h2>Installation</h2>
    <p>
Import the Plugin into the dynaTrace Server. For details how to do this please refer to the <a href="https://community.dynatrace.com/community/display/DOCDT41/Manage+and+Develop+Plugins#ManageandDevelopPlugins-ManageandDevelopPlugins">dynaTrace  documentation</a>.    </p>
    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>