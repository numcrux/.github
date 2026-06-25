# Project Manifesto

## A Reference-Data Commons for ML Numerical Correctness

Machine learning frameworks must be trusted.
To be trusted, they must prove that their numerical results are correct.

Today, every framework keeps its own private or informal test data.
This makes correctness hard to compare, hard to reproduce and hard to cite.

We want to change that.

This project will create an open, neutral and versioned reference-data commons for machine learning numerics. It will provide shared test fixtures, explicit tolerances and reusable tools that framework developers can use to validate their own implementations.

We will start with core tensor operations such as matrix multiplication, selected data types and important edge cases. The first version will be based on the existing numerical test suite from SKaiNET and turned into a public reference suite.

Our goal is simple:

Make numerical correctness testing more transparent, reproducible and comparable across ML frameworks.

The project will provide:

* An open fixture format
* Versioned reference datasets
* Clear numerical tolerances
* Initial test data for basic tensor operations
* Consumer libraries and test runners
* Documentation and examples for easy adoption

This work is framework-agnostic and language-agnostic. It is not built for one project only. It is meant to serve the wider machine learning ecosystem.

We believe correctness should be shared infrastructure.

By making reference data public, citable and reusable, we help developers, researchers and open-source maintainers build more reliable ML systems.
