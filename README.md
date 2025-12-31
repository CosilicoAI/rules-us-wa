# rules-us-wa

Washington State rules encoded in Akoma Ntoso XML format.

## Structure

```
rules-us-wa/
├── statutes/
│   └── rcw/                    # Revised Code of Washington
│       ├── title-82/           # Title 82 - Excise Tax
│       └── title-74/           # Title 74 - Public Assistance
└── regulations/
    └── wac/                    # Washington Administrative Code
```

## Sources

### Statutes

- **Revised Code of Washington (RCW)**: https://app.leg.wa.gov/rcw/
  - Title 82: Excise Tax (sales tax, B&O tax, property tax)
  - Title 74: Public Assistance (TANF, SNAP supplements, child care assistance)

### Regulations

- **Washington Administrative Code (WAC)**: https://app.leg.wa.gov/wac/
  - Implements and interprets RCW provisions
  - Contains detailed eligibility rules and procedures

## Format

All documents are encoded in [Akoma Ntoso](http://www.akomantoso.org/) XML format, an OASIS standard for legislative and legal documents.

## Related Repositories

- [CosilicoAI/arch](https://github.com/CosilicoAI/arch) - Source document archive
- [CosilicoAI/rac](https://github.com/CosilicoAI/rac) - Rules as Code DSL

## License

Source documents are public law. This repository's structure and tooling are MIT licensed.
