# Website Skills

Read skills/build-brand-casino-site/SKILL.md and follow its linked references. Supply a site-specific brief using references/brief.example.json. Keep the complete skill directory together.

Only the BRAND skill is included: the supplied document contained no second site type.

Static QA requires Python 3:

```sh
python3 skills/build-brand-casino-site/scripts/qa_static.py --root ./dist --brief ./brief.json
```

Static QA does not certify browser behavior, legal accuracy or Google rankings. Agents need suitable tools to browse, execute scripts and deploy. Keep secrets out of briefs and Git.
