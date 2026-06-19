```
┌─[ t1m3@root ]─────────────────────────────────────────────┐
│                                                            │
│   offensive security research                              │
│   firmware · hardware · RF/SDR · vuln management           │
│                                                            │
└────────────────────────────────────────────────────────────┘
```

```sh
$ whoami
Senior Cybersecurity Engineer. Vulnerability management at scale,
firmware reverse engineering, coordinated disclosure on embedded
and consumer targets. Heading toward red team / offensive research.

$ cat ~/.now
> ZTE ZXHN F689 V9 — multi-CVE chain, coordinated disclosure in progress
> qjsync — Qualys VMDR → Jira, honest detection lifecycle
> always: firmware teardown, CTF, RF

$ ls research/
```

| target | class | status |
|---|---|---|
| `ZTE ZXHN F689 V9` | pre-auth RCE + multiple CVEs (hardcoded creds, weak crypto) | coordinated disclosure |
| `TP-Link RE305 / Archer C7` | firmware analysis | disclosed |
| `Cubot / YFT (Android)` | zero-permission ContentProvider exposure | disclosed |

```sh
$ ls projects/
```

`qjsync/` &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; transparent Qualys VMDR → Jira connector. QDS prioritisation,
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; KB enrichment, honest lifecycle (purge ≠ remediation)
`flipper-usb-profiler/`  observation-only USB host-behavior profiler for Flipper Zero
`BugChain/` &nbsp;&nbsp;&nbsp; recon / bug-bounty tooling

```sh
$ cat ~/.toolbox
python · c · ghidra · qualys vmdr · docker · linux · gdb · radare2

$ cat ~/.contact
blog → t1m3rev.hashnode.dev
loc  → Brazil
```
