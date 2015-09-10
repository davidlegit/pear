# davidlegit's PEAR Channel Server

Registering the channel:
> pear channel-discover davidlegit.github.com/pear

Listing available packages:
> pear remote-list -c davidlegit

Installing a package:
> pear install davidlegit/package_name

Installing a specific version/stability:
> pear install davidlegit/package_name-1.0.0
> pear install davidlegit/package_name-beta

Receiving updates via a feed:
> http://davidlegit.github.com/pear/feed.xml
