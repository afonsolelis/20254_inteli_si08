# SI08 - Advanced Data Engineering Module

> **Language Note:** This module will be conducted in English to accommodate exchange students participating in the program.

## Project Overview

**TAPI Project:** Creation of a solution for an application using Natural Language for awareness of the preservation of natural means/resources

**Company:** SKZ Oberle LTDA - Corporate solutions hub with 80+ years of market experience in accounting, financial BPO, and tax consulting.

**Supervising Professor:** Hermano Peixoto

## Project Team

- **Project Leader:** Fabio Oberle (Commercial Director)
- **Technical Leader:** Kaic Fachinetti (Developer)
- **Business Leader:** Ricardo Evangelista (Data Analyst)
- **Executive Leader:** Alexandre Tamura (IT Director)
- **Backup Focal Point:** Paulo Ricardo (Developer)

## Problem Statement

SKZ Oberle lacks a unified and accessible data infrastructure for fast, traceable, and secure access to accounting, tax, and financial information. Data is fragmented across multiple sources (ERP systems, SQL databases, spreadsheets, manual files), hindering analytical solutions and future AI integrations.

## Project Objective

Establish a robust corporate data platform by integrating, organizing, and centralizing accounting, tax, and financial data. Build a structured, secure, and auditable foundation for efficient internal data consumption and future natural language-based AI financial assistant implementation.

## Expected Benefits

- Automated data ingestion from multiple sources (ERPs, SQL databases, spreadsheets)
- Data organization, cleaning, standardization, and enrichment
- Centralized storage in Data Lake or Data Warehouse
- Data availability through APIs, data views, or query tools
- Implementation of security, access control, and traceability policies

## Project Scope

### MVP Deliverable
First version of Big Data pipeline integrating and centralizing SKZ Oberle's main accounting, tax, and financial data with automated ingestion, structured storage, and controlled access.

### Sprint Deliverables
- **Sprint 1:** User understanding and business understanding
- **Sprint 2:** Data ingestion system
- **Sprint 3:** Data Lake or Data Warehouse
- **Sprint 4:** Statistical analysis without refinement
- **Sprint 5:** Infographic from statistical analysis

## Technical Requirements

### Development Environment (Mandatory)
- **Node.js:** v20.x LTS
- **Python:** 3.12.x
- **Poetry:** Python dependency management
- **Git:** Version control
- **Docker:** Containerized environment

### Infrastructure
- Project must run in Dockerized environment
- Minimum 1 GB dataset simulation
- Azure resources available (no dedicated data infrastructure yet)

## Development Standards

### Conventional Commits (Mandatory)
**Format:** `<type>[optional scope]: <description>`

**Types:**
- `feat`: New functionality
- `fix`: Bug fixes
- `docs`: Documentation changes
- `refactor`: Code refactoring
- `test`: Test additions/modifications
- `build`: Build system changes
- `ci`: CI/CD changes
- `chore`: Maintenance tasks

**Rules:**
- Present tense, imperative mood
- Max 72 characters for first line
- No periods at end of description
- No emojis or vague messages

### GitFlow Workflow
- **Main:** Production-ready code
- **Develop:** Integration branch for features
- **Feature Branches:** Individual feature development
- **Release Branches:** Pre-release preparation
- **Hotfix Branches:** Critical bug fixes

### Code Quality Standards
- **Clean Code:** Self-documenting code without extensive comments
- **OOP Principles:** Encapsulation, inheritance, polymorphism
- **ETL Best Practices:** Well-structured Extract, Transform, Load processes
- **Documentation:** MkDocs and project office standards

## Module Structure

### Week 02 - Advanced Exploratory Data Analysis & Data Architecture

#### 1. Advanced Exploratory Data Analysis with Jupyter + Poetry
- Jupyter Notebook best practices
- Poetry for dependency management
- Advanced data visualization techniques
- Statistical analysis and hypothesis testing
- Data quality assessment and profiling

#### 2. Data Lake Creation and Management
- Data Lake architecture patterns
- Data ingestion strategies
- Data partitioning and optimization
- Metadata management
- Data governance principles

#### 3. Data Architecture with UML Component Diagrams (Medallion Architecture)
- Medallion Architecture (Bronze, Silver, Gold layers)
- UML Component Diagrams for data systems
- Data flow design and documentation
- Scalability and performance considerations
- Integration patterns

#### 4. Data Pricing and Cost Optimization
- Cloud data platform pricing models
- Cost optimization strategies
- Resource allocation and monitoring
- ROI analysis for data projects
- Budget planning and forecasting

## Timeline and Milestones

### Phase 1: Foundation (Weeks 1-2)
- Environment setup and tooling
- Basic data analysis techniques
- Git workflow establishment
- Initial architecture planning

### Phase 2: Advanced Analysis (Weeks 3-4)
- Advanced exploratory data analysis
- Data quality assessment
- Statistical analysis implementation
- Visualization and reporting

### Phase 3: Architecture and Implementation (Weeks 5-6)
- Medallion architecture design
- Data pipeline implementation
- UML documentation
- Cost optimization analysis

### Phase 4: Integration and Optimization (Weeks 7-8)
- System integration
- Performance optimization
- Documentation completion
- Final presentation and review

## Assessment Criteria

### Technical Implementation (40%)
- Code quality and architecture
- Functionality and performance
- Best practices adherence

### Documentation (30%)
- Technical documentation quality
- Architecture diagrams and specifications
- Process documentation

### Professional Practices (30%)
- Git workflow compliance
- Commit message standards
- Collaboration and communication

## Tools and Technologies

### Development Environment
- **Python:** Primary programming language
- **Jupyter Notebooks:** Interactive development and analysis
- **Poetry:** Dependency management
- **Git:** Version control
- **MkDocs:** Documentation generation

### Data Platforms
- **Cloud Platforms:** AWS, Azure, or GCP
- **Data Storage:** Data Lakes, Data Warehouses
- **Processing:** Spark, Pandas, Dask
- **Visualization:** Matplotlib, Seaborn, Plotly

### Architecture Tools
- **UML Tools:** Draw.io, Lucidchart, or similar
- **Documentation:** MkDocs, Sphinx
- **CI/CD:** GitHub Actions, GitLab CI, or similar

## Development Tools Setup

### Qwen Code CLI
```bash
# Install via pip
pip install qwen-code-cli

# Usage
qwen-code commit --ai
qwen-code analyze
```

### GitHub CLI
```bash
# Linux
curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null
sudo apt update
sudo apt install gh

# Usage
gh auth login
gh pr create --title "feat(scope): add new functionality"
```

## Project Restrictions

- Integrations limited to explicitly mentioned systems
- No advanced ML/neural networks beyond descriptive statistics
- No front-end/dashboard development
- No external data access or public APIs
- 70 calendar days completion timeline

## Success Metrics

### Technical Metrics
- Code coverage and quality scores
- Performance benchmarks
- Architecture compliance
- Documentation completeness

### Professional Metrics
- Commit message compliance
- Git workflow adherence
- Collaboration effectiveness
- Project delivery timeliness

## Resources

### Documentation
- [Conventional Commits Specification](https://www.conventionalcommits.org/)
- [GitFlow Documentation](https://nvie.com/posts/a-successful-git-branching-model/)
- [Clean Code Principles](https://clean-code-developer.com/)

### Technical Resources
- [Data Engineering Best Practices](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/)
- [Medallion Architecture Guide](https://www.databricks.com/glossary/medallion-architecture)
- [UML for Data Systems](https://www.uml.org/)

## Stakeholders

- **Marcio Tamura** - Executive Director
- **Gustavo Prado** - Financial Director
- **Adalberto Tamura** - Operations Director
- **Fernando Oberle** - Technical Director
- **Aloisio Defensor** - Operations Director - Portugal
- **SKZ Oberle Team**

---

*This module prepares students for real-world data engineering challenges with emphasis on clean code, proper documentation, and professional collaboration practices.*