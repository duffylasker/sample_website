# sample_website
website to learn html
<h2>Unattended upgrades</h2>
===================

<p>This script can upgrade packages automatically and unattended.
However, it is not enabled by default.  Most users enable it via the
Software Sources program (available in System/Administration).

If you would prefer to enable it from the command line, run
"sudo dpkg-reconfigure -plow unattended-upgrades".

It will not install packages that require dependencies that can't be
fetched from allowed origins and it will check for conffile prompts
before the install and holds back any package that requires them.
</p>
