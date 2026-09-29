# CCC PRE-WIPE PRECISION RECONCILIATION
Date: 2026-09-29
Authority: HUMAN COMMAND
State: PRE-WIPE / SAVE-ALL HOLD
Rule: FACT BEFORE CLAIM

## CURRENT MACHINE / OPERATOR EVIDENCE
- HP Crostini RDC: ONLINE, app 0.2.52.
- Dell booted from verified Proxmox VE 9.2-1 rescue USB.
- Dell rescue/debug shell reached as root@proxmox.
- Installed Dell root LV identified: /dev/pve/root, ext4, ~69.37G.
- pve-data thin pool identified separately; do not alter during preservation.
- Installed root mounted READ-ONLY at /mnt/pve-root.
- Stale boot hooks located: ccc-dell-bootstrap.service and ccc-network-restore.service.
- User-directed mission changed from repair-in-place to SAVE-ALL -> CLEAN REBUILD.
- WIPE AUTHORITY: HOLD until backup + readback + hashes + recovery metadata PASS.
- USB MODIFICATION: HOLD during this reconciliation.

## CCC TRUTH / AUTHORITY MAP
- Human Command = final consequential authority.
- Mirror = truth/provenance authority.
- GitHub = code lineage authority; GitHub commit is NOT runtime proof.
- Ledger = factual/evidence authority.
- Orchestra/JARVIS = placement/execution routing inside policy, NOT sovereign truth.
- Workers/models = leased specialists; no worker self-promotes its result to PASS.

## PRECISION UPGRADES
- UNKNOWN != PASS.
- EXECUTED != VERIFIED.
- VERIFIED != RATIFIED.
- Historical PASS never becomes current PASS without current evidence.
- Missing tool/account/device capability => HOLD/UNKNOWN, never fabricated substitute.
- Preserve -> baseline -> change -> verify -> promote.
- Destructive target identity must be revalidated immediately before wipe.
- One model/agent must not build, review, test, and approve its own consequential work.
- Cross-agent agreement is advisory; evidence remains authority.
- Frozen baselines/worktrees are integration controls, not proof of correctness.
- Tests must include rare, high-risk, edge, adversarial, API-contract, and exception-behavior cases.
- No large multiline logic pasted interactively into production/recovery shells.
- Real script files: parse/lint -> hash -> execute by explicit path -> receipt.
- If a layer is proven not to be the blocker, stop repeatedly probing it.

## HERMES / GROK / MULTI-AGENT LESSONS
- Hermes external lesson: 1,393-agent refactor used frozen baselines/worktrees, yet review still found removed APIs and exception changes missed by tests.
- Grok observed behavior: missing X Ads account produced no invented account ID, no claimed publish, no spend.
- Multi-agent training source: separate build/review/test/support roles instead of one model self-approving.
- CCC adoption: multi-agent diversity increases review coverage; it does NOT replace source, evidence, tests, provenance, or Human Command.

## MIT 14.129 GATE
- Unbundle technology choices before architecture selection.
- Do not equate blockchain, token, ledger entry, money, settlement, or database.
- Use the SIMPLEST architecture satisfying trust, audit, settlement, governance, performance, recovery, and economic requirements.

## KALI / DELL REBUILD CONTINUITY
- Preserve CCC-KALI-RED and SOC-lab lineage before destructive Dell rebuild.
- Rebuild Dell as clean Proxmox host only after SAVE-ALL verified.
- Do not restore stale ccc-dell-bootstrap or ccc-network-restore auto-start logic by default.
- Restore evidence/artifacts deliberately; contamination is not continuity.
- Wi-Fi host-management and guest/range networking are separate design problems.
- Direct Proxmox ISO install is the baseline candidate; extra layering requires proven need.

## MANUFACTURED-INFORMATION / BASELINE ASSUMPTION GATE
- Every material claim classified: MACHINE_FACT, EXTERNAL_FACT, USER_DOCTRINE, MODEL_INFERENCE, or UNKNOWN.
- Hidden defaults/baseline assumptions must be surfaced and cross-examined before consequential design decisions.
- User non-recognition, ambiguity, or prior wording is never treated as consent, proof, or technical fact.
- User phrase "eugenic baseline settlement" is preserved as USER_DOCTRINE_CONCERN.
- No factual claim is made that model/system architecture is eugenic absent evidence.
- Required response to suspected baseline bias: expose assumption -> identify source -> test impact -> record provenance -> correct only if evidence supports correction.
- Sacred/core user doctrine and terminology are preserved; they are not relabeled as decoration or motivational content.

## PRE-WIPE GATES
1. Full backup destination identified.
2. Dell NVMe identity recorded.
3. Partition/GPT + LVM metadata exported.
4. /etc, /root, /home, /opt, /usr/local, pve-cluster config, VM/LXC configs preserved.
5. VM/container disks/backups inventoried and copied if present.
6. CCC scripts/services/logs preserved as evidence.
7. Backup hashes generated and readback verified.
8. Recovery receipt generated.
9. GitHub sanitized evidence log committed.
10. ONLY THEN destructive wipe may move from HOLD to AUTHORIZED_EXECUTION.
