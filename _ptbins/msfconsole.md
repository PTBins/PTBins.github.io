---
description: This allows to spawn a [`ruby`](/ptbins/ruby/) interpreter.
functions:
  shell:
    - code: |
        sudo msfconsole
        msf6 > irb
        >> system("/bin/sh")
  sudo:
    - code: |
        sudo msfconsole
        msf6 > irb
        >> system("/bin/sh")
---
