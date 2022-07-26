
Documentation is key for any project success. When team members move to different projects, the **[Tribal Knowledge](https://www.lucidchart.com/blog/what-is-tribal-knowledge)** will be lost, and it would be hard for new maintainers keep the project on track as per the original *Roadmap*. I believe in [Docs as Code](https://www.writethedocs.org/guide/docs-as-code/) philosophy and keep related documents close to code in the same repository.

Docs should be organized under `docs` folder in the root of the repo.
I recommend [GitHub Flavored Markdown](https://github.github.com/gfm/) for writing documents and leverage [draw.io](https://app.diagrams.net/) and [Mermaid](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/) to embed diagrams directly into *Markdown* files.
Recommended minimal documentation for each project:

### Readme File
It Should contain Project goals, big picture, list of features, developer's workflow to contribute to repo.

### Project Boards
[Project Boards](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards) to keep tracking releases, milestones, features and project status.

### Roadmap
It should include short and long term goals.

### Changelog
Automatically [generate](https://github.com/crestamr/AutomaticChangeLog) changelog as part for release process.

### Code Owners
**[Code Owners](https://docs.gitlab.com/ee/user/project/code_owners.html)** - [CODEOWNERS](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners) file contain resources who own specific module in the repository and who should review before PRs are merged.

**Example CODEOWNERS file**
![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1658798814845/UAgZE4BIc.png align="left")

### Architecture Decision Record (ADR)
It is a document that captures an important architectural decision made along with its context and consequences.

**Style Guide**
- This folder should contain all ADR docs
- I followed ADR file name conventions from [Joel Parker](https://github.com/joelparkerhenderson/architecture_decision_record)
- Markdown Architectural Decision Records [template](https://adr.github.io/madr/)

**ADR example templates**

ADR example templates that I have collected on the net:

* [ADR template by Michael Nygard](https://github.com/crestamr/docs/blob/main/adr/template/adr_template_by_michael_nygard.md) (simple and popular)
* [ADR template MADR](https://github.com/crestamr/docs/blob/main/adr/template/adr_template_madr.md) (more Markdown)



### Style Guide
- Coding Style Guide

## Reference
- [joelparkerhenderson/architecture_decision_record](https://github.com/joelparkerhenderson/architecture_decision_record)
- [Solution Architecture Patterns](https://github.com/chanakaudaya/solution-architecture-patterns)
