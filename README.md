# tas-pipeline-examples

* CI pipelines example files to showcase how to integrate the different TSSC (Trusted Software Supply Chain) products to secure a pipeline.
The different products used are:
 - Trusted Artifact Signer (TAS) for checking source commit signing using gitsign
 - Trusted Artifact Signer (TAS) for signing the container image, attesting the SLSA predicate and attesting the SBOM using cosign
 - Advanced Cluster Security (ACS) for image scannning and checking for vulnerabilities
 - Enterprise Contract (EC) for validating the container image attestation against a SLSA Level 2 policy
 - Upload the SBOM produced by Syft to Trusted Profile Analyzer (TPA) 

