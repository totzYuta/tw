Simple Twitter Client
=====================
* one file twitter client.
* Ruby 1.8.7 / 1.9.2 / JRuby 1.6.0.
* for UNIX, Linux and Mac OSX.


Install
-------

    % git clone git://github.com/shokai/simple-twitter-client.git
    % cp simple-twitter-client/twitter /path/to/somewhere/
    % which twitter


Install Dependencies
--------------------

    % gem install oauth twitter


Use
---

tweet

    % twitter hello hello
    % twitter @shokai こにちわ


mentions

    % twitter


user timeline

    % twitter @shokai
    % twitter @shokai @ymrl @tomoyo_kousaka


list timeline

    % twitter @shokai/hoge
    % twitter @shokai/hoge @shokai/kzsk
