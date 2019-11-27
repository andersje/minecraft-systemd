look, the code has the link to the original stuff, which is definitely what you want.  
i just saved this stuff here because it's free, and i don't want to lose this code.

Here's how i setup all my minecraft servers, so they start at boot now, after copying the files into place in /etc/systemd/system.


  systemctl daemon-refresh
  systemctl enable mitchellbot@vlad2
  systemctl start mitchellbot@vlad2
  systemctl enable mitchellbot@skovunia
  systemctl start mitchellbot@skovunia
  systemctl start aof_mc
  systemctl enable aof_mc
  systemctl enable mitchellbot@kimjongun
  systemctl start mitchellbot@kimjongun
  systemctl enable mitchellbot@duterte
  systemctl start mitchellbot@duterte
