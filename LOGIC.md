```mermaid
flowchart TD
    User --> CloudFront
    CloudFront --> ACM
    CloudFront --> S(S3 Bucket)
```