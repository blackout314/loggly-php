Fixed Loggly Php Lib
==============



Getting Started
===============

The first step is to instantiate a new instance of the Loggly class:


    $loggly = new Loggly();

    $loggly->subdomain = '<loggly subdomain>';

    $loggly->username = 'demo';

    $loggly->password = '42ftw';

Search Methods
==============



###Searching
    
    $result = $loggly->search('unix', array('from' => 'NOW-3HOURS', 'until' => 'NOW-1HOUR'));

###Events

    $result = $loggly->events(array('rsid' => <RSID>));

