# scripts

Basic Scripts to automate tedious stuff.

# 1. tor_custom_configuration_gh.sh

This script automates the installation and configuration process of setting up tor, proxychains and privoxy to redirect all  traffic through Tor. 

The following __packages__ are installed:
 * Curl
 * Tor
 * Proxychains
 * Privoxy

  Optional (terminal browsers):
    * Lynx
    * W3m

The following __changes__ are applied:
  * Proxychains
    * SOCKS5 and dynamic_chain in /etc/proxychains.conf
  * Privoxy
    * forward_socks5 in n/etc/privoxy/config

