Haproxy
~~~~~~~

.. csv-table:: Resources (ExportController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","haproxy","export","config",""
    "``GET``","haproxy","export","diff",""
    "``GET``","haproxy","export","download","$type"

.. csv-table:: Resources (MaintenanceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","haproxy","maintenance","cert_actions",""
    "``GET``","haproxy","maintenance","cert_diff",""
    "``GET``","haproxy","maintenance","cert_sync",""
    "``GET``","haproxy","maintenance","cert_sync_bulk",""
    "``POST``","haproxy","maintenance","fetch_cron_integration",""
    "``GET``","haproxy","maintenance","get",""
    "``GET``","haproxy","maintenance","search_certificate_diff",""
    "``GET``","haproxy","maintenance","search_server",""
    "``GET``","haproxy","maintenance","server_state",""
    "``GET``","haproxy","maintenance","server_state_bulk",""
    "``GET``","haproxy","maintenance","server_weight",""
    "``GET``","haproxy","maintenance","server_weight_bulk",""
    "``POST``","haproxy","maintenance","set",""

    "``<<uses>>``", "", "", "", "*model* `HAProxy.xml <https://github.com/opnsense/plugins/blob/master/net/haproxy/src/opnsense/mvc/app/models/OPNsense/HAProxy/HAProxy.xml>`__"

.. csv-table:: Service (ServiceController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","haproxy","service","configtest",""
    "``POST``","haproxy","service","reconfigure",""
    "``POST``","haproxy","service","restart",""
    "``POST``","haproxy","service","start",""
    "``GET``","haproxy","service","status",""
    "``POST``","haproxy","service","stop",""

    "``<<uses>>``", "", "", "", "*model* `HAProxy.xml <https://github.com/opnsense/plugins/blob/master/net/haproxy/src/opnsense/mvc/app/models/OPNsense/HAProxy/HAProxy.xml>`__"

.. csv-table:: Resources (SettingsController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``POST``","haproxy","settings","add_acl",""
    "``POST``","haproxy","settings","add_action",""
    "``POST``","haproxy","settings","add_backend",""
    "``POST``","haproxy","settings","add_cpu",""
    "``POST``","haproxy","settings","add_errorfile",""
    "``POST``","haproxy","settings","add_fcgi",""
    "``POST``","haproxy","settings","add_frontend",""
    "``POST``","haproxy","settings","add_group",""
    "``POST``","haproxy","settings","add_healthcheck",""
    "``POST``","haproxy","settings","add_lua",""
    "``POST``","haproxy","settings","add_mapfile",""
    "``POST``","haproxy","settings","add_server",""
    "``POST``","haproxy","settings","add_user",""
    "``POST``","haproxy","settings","addmailer",""
    "``POST``","haproxy","settings","addresolver",""
    "``POST``","haproxy","settings","del_acl","$uuid"
    "``POST``","haproxy","settings","del_action","$uuid"
    "``POST``","haproxy","settings","del_backend","$uuid"
    "``POST``","haproxy","settings","del_cpu","$uuid"
    "``POST``","haproxy","settings","del_errorfile","$uuid"
    "``POST``","haproxy","settings","del_fcgi","$uuid"
    "``POST``","haproxy","settings","del_frontend","$uuid"
    "``POST``","haproxy","settings","del_group","$uuid"
    "``POST``","haproxy","settings","del_healthcheck","$uuid"
    "``POST``","haproxy","settings","del_lua","$uuid"
    "``POST``","haproxy","settings","del_mapfile","$uuid"
    "``POST``","haproxy","settings","del_server","$uuid"
    "``POST``","haproxy","settings","del_user","$uuid"
    "``POST``","haproxy","settings","delmailer","$uuid"
    "``POST``","haproxy","settings","delresolver","$uuid"
    "``GET``","haproxy","settings","get",""
    "``GET``","haproxy","settings","get_acl","$uuid=null"
    "``GET``","haproxy","settings","get_action","$uuid=null"
    "``GET``","haproxy","settings","get_backend","$uuid=null"
    "``GET``","haproxy","settings","get_cpu","$uuid=null"
    "``GET``","haproxy","settings","get_errorfile","$uuid=null"
    "``GET``","haproxy","settings","get_fcgi","$uuid=null"
    "``GET``","haproxy","settings","get_frontend","$uuid=null"
    "``GET``","haproxy","settings","get_group","$uuid=null"
    "``GET``","haproxy","settings","get_healthcheck","$uuid=null"
    "``GET``","haproxy","settings","get_lua","$uuid=null"
    "``GET``","haproxy","settings","get_mapfile","$uuid=null"
    "``GET``","haproxy","settings","get_server","$uuid=null"
    "``GET``","haproxy","settings","get_user","$uuid=null"
    "``GET``","haproxy","settings","getmailer","$uuid=null"
    "``GET``","haproxy","settings","getresolver","$uuid=null"
    "``*``","haproxy","settings","search_acls",""
    "``*``","haproxy","settings","search_actions",""
    "``*``","haproxy","settings","search_backends",""
    "``*``","haproxy","settings","search_cpus",""
    "``*``","haproxy","settings","search_errorfiles",""
    "``*``","haproxy","settings","search_fcgis",""
    "``*``","haproxy","settings","search_frontends",""
    "``*``","haproxy","settings","search_groups",""
    "``*``","haproxy","settings","search_healthchecks",""
    "``*``","haproxy","settings","search_luas",""
    "``*``","haproxy","settings","search_mapfiles",""
    "``*``","haproxy","settings","search_servers",""
    "``*``","haproxy","settings","search_users",""
    "``*``","haproxy","settings","searchmailers",""
    "``*``","haproxy","settings","searchresolvers",""
    "``POST``","haproxy","settings","set",""
    "``POST``","haproxy","settings","set_acl","$uuid"
    "``POST``","haproxy","settings","set_action","$uuid"
    "``POST``","haproxy","settings","set_backend","$uuid"
    "``POST``","haproxy","settings","set_cpu","$uuid"
    "``POST``","haproxy","settings","set_errorfile","$uuid"
    "``POST``","haproxy","settings","set_fcgi","$uuid"
    "``POST``","haproxy","settings","set_frontend","$uuid"
    "``POST``","haproxy","settings","set_group","$uuid"
    "``POST``","haproxy","settings","set_healthcheck","$uuid"
    "``POST``","haproxy","settings","set_lua","$uuid"
    "``POST``","haproxy","settings","set_mapfile","$uuid"
    "``POST``","haproxy","settings","set_server","$uuid"
    "``POST``","haproxy","settings","set_user","$uuid"
    "``POST``","haproxy","settings","setmailer","$uuid"
    "``POST``","haproxy","settings","setresolver","$uuid"
    "``POST``","haproxy","settings","toggle_backend","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggle_cpu","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggle_frontend","$uuid"
    "``POST``","haproxy","settings","toggle_group","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggle_lua","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggle_server","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggle_user","$uuid,$enabled=null"
    "``POST``","haproxy","settings","togglemailer","$uuid,$enabled=null"
    "``POST``","haproxy","settings","toggleresolver","$uuid,$enabled=null"

    "``<<uses>>``", "", "", "", "*model* `HAProxy.xml <https://github.com/opnsense/plugins/blob/master/net/haproxy/src/opnsense/mvc/app/models/OPNsense/HAProxy/HAProxy.xml>`__"

.. csv-table:: Resources (StatisticsController.php)
   :header: "Method", "Module", "Controller", "Command", "Parameters"
   :widths: 4, 15, 15, 30, 40

    "``GET``","haproxy","statistics","counters",""
    "``GET``","haproxy","statistics","info",""
    "``GET``","haproxy","statistics","tables",""
