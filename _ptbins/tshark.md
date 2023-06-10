---
description: This program is able to execute [`lua`](/ptbins/less/) code.
functions:
  shell:
    - code: |
        TF=$(mktemp)
        echo 'os.execute("/bin/sh")' >$TF
        tshark -Xlua_script:$TF
---
