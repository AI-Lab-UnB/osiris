# OSIRIS Framework

OSIRIS is an open-source framework designed to streamline and enhance the tax foreclosure process in Brazil through the application of artificial intelligence. By leveraging modern AI technologies, OSIRIS aims to reduce operational bottlenecks, improve accuracy, and accelerate the resolution of tax-related legal proceedings.

## Project Overview

The OSIRIS framework consists of several specialized components, each addressing specific challenges in the tax foreclosure workflow:

### osiris-extraction
A data extraction system that interfaces with Brazilian lawsuit management systems like PJe (Processo Judicial Eletrônico). This component automates the collection and preprocessing of legal documents and case information, ensuring a consistent data flow to other framework components.

Key features:
- Automated data extraction from PJe and similar systems
- Standardized data formatting for downstream processing
- Robust error handling and validation
- Real-time synchronization capabilities

### osiris-agent
An intelligent agent system that processes structured legal data and provides actionable insights to operators. This component streamlines decision-making by analyzing case information and suggesting optimal next steps in the foreclosure process.

Key features:
- Natural language processing of legal documents
- Context-aware recommendation system
- Workflow optimization
- Interactive operator interface

### osiris-doc-classifier
A machine learning solution that automatically classifies legal documents based on their source and content. This component helps organize and prioritize documents from different stakeholders in the foreclosure process.

Key features:
- Multi-class document classification
- Source identification (creditor, debtor, court)
- Confidence scoring
- Continuous learning capabilities

### osiris-spliter
A document processing tool that breaks down multi-document PDFs into individual, atomic documents for more efficient processing. This component ensures that each document can be properly analyzed and classified by other parts of the framework.

Key features:
- Intelligent PDF parsing and segmentation
- Document boundary detection
- Metadata preservation
- Quality control checks

## Getting Started

Each component of the OSIRIS framework has its own repository with specific setup instructions and documentation. Please visit the individual repositories for detailed information:

- [osiris-extraction](link-to-repo)
- [osiris-agent](link-to-repo)
- [osiris-doc-classifier](link-to-repo)
- [osiris-spliter](link-to-repo)

## Acknowledgments

This project is sponsored by the Fundação de Apoio à Pesquisa do Distrito Federal (FAPDF). Their support has been instrumental in the development and advancement of the OSIRIS framework.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2025 OSIRIS Framework

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

