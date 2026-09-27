# Awesome AI Creator Rights [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Sources and tools for people who make music, images, characters and video with AI: whether the result is protected, what the tool's terms let you do, how to show you made it first, and what to do when someone copies it.

**Not legal advice.** This list collects primary sources — statutes, court decisions, agency guidance and the tools' own terms — so you can read them yourself. The law differs by country and changes quickly; each section shows when it was last checked. For a decision about your own work, talk to a lawyer where you live.

[繁體中文版](README.zh-TW.md)

## Contents

- [Is AI-generated work protected?](#is-ai-generated-work-protected)
- [Who owns the output: AI tool terms](#who-owns-the-output-ai-tool-terms)
- [Proving you made it first](#proving-you-made-it-first)
- [When someone copies your work](#when-someone-copies-your-work)
- [Licensing and selling](#licensing-and-selling)
- [Labelling and transparency rules](#labelling-and-transparency-rules)
- [Further reading](#further-reading)

## Is AI-generated work protected?

Most copyright systems protect only what a human author contributed. What counts as enough human contribution — prompts, selection, editing, arrangement — is decided country by country.

<!-- section1 -->

## Who owns the output: AI tool terms

A tool's terms decide what you may do with the output as between you and the company. They cannot make output copyrightable where the law says it is not (see the section above).

<!-- section2 -->

## Proving you made it first

If a dispute comes, the first question is often simply who had the work first. These methods record that a file existed at a certain time. None of them, on its own, proves who created it or who owns the rights.

*Last verified: 2026-09-27.*

| Method | Shows the file existed by a date | Shows who made it | Cost | Checkable without the provider |
|---|---|---|---|---|
| Notarial authentication (Taiwan 認證) | Yes, what the notary saw | No | About NT$500 (statutory base) | Yes, public record |
| Taiwan certified letter (存證信函) | Yes, text and mailing date | No | NT$50 + NT$30 per extra page, plus postage | Post office keeps its copy 3 years |
| RFC 3161 timestamp (e.g. FreeTSA) | Yes | No | Free (FreeTSA) | Yes, with OpenSSL |
| eIDAS qualified timestamp | Yes, with a legal presumption in the EU | No | Varies by provider | Yes |
| OpenTimestamps | Yes, anchored in Bitcoin | No | Free | Yes |
| Commercial blockchain services | Yes | No | Paid plans, or on quote | Depends on export |
| OpenStela | Yes, anchored nightly on Arbitrum One | No | Free to register | Yes, with the Merkle proof in the Proof Pack |
| C2PA / Content Credentials | Records a signed edit history | Names the signer, often the tool | Free standard | Yes, but metadata can be stripped |
| US copyright registration | Effective date of registration | Prima facie evidence, if filed within 5 years of publication | US$45–125 | Yes, public record |
| Emailing yourself / cloud history | Weakly | No | Free | No |

### Official records

- [Taiwan Notary Act (公證法)](https://law.moj.gov.tw/LawClass/LawAll.aspx?pcode=B0010010) - A court or private notary can authenticate a signed declaration with printouts or file hashes; authenticated documents are presumed genuine ([Code of Civil Procedure §358](https://law.moj.gov.tw/LawClass/LawSingle.aspx?pcode=B0010001&flno=358)). It records what the notary saw, not who created the work.
- [Taiwan certified-content letter (存證信函)](https://www.post.gov.tw/post/internet/Customer_service/index.jsp?ID=1610075122269) - Chunghwa Post keeps an identical copy and certifies only that the copies match and the mailing date. Text only, Chinese form, and the post office keeps its copy for three years.
- [US copyright registration](https://www.copyright.gov/registration/) - Registration within five years of publication is prima facie evidence ([17 U.S.C. §410(c)](https://www.law.cornell.edu/uscode/text/17/410)). AI-generated material beyond de minimis must be disclosed and excluded ([88 FR 16190](https://www.federalregister.gov/documents/2023/03/16/2023-05321/copyright-registration-guidance-works-containing-material-generated-by-artificial-intelligence)); fees are [US$45–125](https://www.copyright.gov/about/fees.html).
- [No registration in Taiwan (TIPO)](https://www.tipo.gov.tw/tw/copyright/692-16449.html) - Taiwan abolished copyright registration in 1998; the author bears the burden of proof and is advised to keep records of the creation process ([TIPO on proof](https://www.tipo.gov.tw/tw/copyright/696-21213.html)).

### Timestamps

- [RFC 3161](https://www.rfc-editor.org/rfc/rfc3161) - The standard for trusted timestamps: a Time Stamping Authority signs a token binding your file's hash to a time. Only the hash leaves your computer.
- [FreeTSA](https://freetsa.org/index_en.php) - A free RFC 3161 authority usable with OpenSSL. Keep the original bytes: re-exporting a file changes its hash.
- [eIDAS Article 41](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32014R0910) - In the EU, only a *qualified* electronic timestamp carries a presumption of accurate date and data integrity; other timestamps are still admissible as evidence.
- [OpenTimestamps](https://opentimestamps.org/) - Free, no account, anchored in Bitcoin. Confirmation takes a few hours; run `ots upgrade` so the proof can be checked without the calendar servers.

### Blockchain registries

- [Bernstein](https://www.bernstein.io/) - Web app for registering designs and drafts with Bitcoin anchoring and qualified timestamps; paid plans. Its marketing speaks of ownership, but a timestamp proves existence, not ownership.
- [OriginStamp](https://originstamp.com/en/timestamp) - Blockchain timestamping for businesses via API; pricing on request.
- [OpenStela](https://openstela.io) - Free registry for AI characters and works; fingerprints are anchored nightly on Arbitrum One and the downloadable Proof Pack carries the Merkle proof. Its [terms](https://openstela.io/terms) state it is not proof of authorship or ownership. *Disclosure: this list is maintained by OpenStela.*

### Provenance metadata

- [C2PA / Content Credentials](https://contentcredentials.org/) - A signed record of how a file was made and edited, often added by the tool itself. It names the signer, not necessarily the creator, and [can be stripped](https://spec.c2pa.org/specifications/specifications/2.2/explainer/Explainer.html); pair it with an independent timestamp.

### What does not work well

- [Emailing a copy to yourself](https://www.copyright.gov/help/faq/faq-general.html) - The US Copyright Office says this "poor man's copyright" has no legal basis. Cloud version history and file dates are easy to dispute; use them only as supporting evidence.
- [WIPO PROOF](https://www.wipo.int/wipoproof/en/) - Discontinued: no new tokens since 31 January 2022. Existing tokens remain verifiable.

## When someone copies your work

<!-- section4 -->

## Licensing and selling

<!-- section5 -->

## Labelling and transparency rules

<!-- section6 -->

## Further reading

<!-- section7 -->

## Contributing

Corrections and additions are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). Every entry needs a source.

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](LICENSE)

Maintained by [OpenStela](https://openstela.io). Licensed under [CC BY 4.0](LICENSE): you may share and adapt this list, with attribution.
