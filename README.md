# RunUO Remote Admin Enrichment

## Introduction

##### Web admin control panel for RunUO plus enriched admin features

This project contains PHP scripts and web page control panel to control RunUO shard. A feature enrichment script also included in this project to allow you to broadcast, save, restart, shutdown your RunUO shard using web interface. The web interface does not have to be on the same server with your RunUO. It can connect to any running RunUO server which you have staff account on it.

Basic remote admin features provided in RunUO official code:

* Search RunUO game account __implemtation incomplete in current version of web control panel__
* Add RunUO game account
* Modify RunUO game account
  + Change password
  + Change access level
  + Ban account
* Remove RunUO game account __not provided in current version of web control panel__
* Add IP restriction to RunUO game account __not provided in current version of web control panel__

Enriched remote admin features in this project:

* Broadcast on RunUO shard __same as you broadcast in game using staff account__
* Save RunUO shard instantly
* Restart RunUO shard
* Shutdown RunUO shard

You may also add functionality of creating new RunUO account instantly to your shard website, using the PHP function library in this project.

### A quick installation guideline

Extract the archived file. You will see two directories.


#### RunUO server side

In RunUO_script directory, copy the __CustomRemoteAdminPacketHandlers.cs__ into anywhere of your RunUO Scripst directory. You may start your RunUO server now.


#### Web server side

Upload all files under __web_control_panel__ directory onto your web server directory. Browse the __runuo_remote_admin.php__, you will see a logon page. Input the RunUO server IP/domain, port, then your RunUO admin account to login. The RunUO account can be administrator, owner, developer or game master access level in RunUO server.
