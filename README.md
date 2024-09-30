## Slide no. 18
### Slide Title: Multiple Regions

**Issue:** Text got cut off at last line

## Slide no.19
### Region

**Change:** Google Cloud now has **40 regions**, the slide mentions 20+.

## Slide no. 20
### Zones

**Actual Text:** Each region has three or more zones.  
**Change:** Some regions may have **two** zones (especially newer or smaller regions).

## Slide no.  27
### Compute Engine Machine Families

There are two new machine families:  **Storage Optimized** and  **GPU**

- **Storage Optimized (Z3) :** Machine types for storage-intensive workloads, like horizontal, scale-out databases.

- **GPU (N1) :** Graphics processing units (GPUs) accelerate specific workloads on your instances such as machine learning and data processing. 


## Slide no.  33
### Static IP Addresses - Remember

Not an error, just a simple typo. Instead of **an Static IP**, there should be **a Static IP**.


## Slide no. 73
### Committed use discounts

**Suggestion:** The slide mentions that "Up to 70% discount based on machine type and GPUs." This can be made clearer by saying: The discount is up to 55% for most resources, like machine types or GPUs. The discount is up to 70% for memory-optimized machine types.

**Source:** https://cloud.google.com/compute/docs/instances/signing-up-committed-use-discounts

 - **Can be included in slide:**
	- Committed use discounts don't apply to preemptible VM instances, N1 shared-core machine types, or extended memory.

## Slide no. 79
### Gcloud

**Suggestion:** Google Cloud now recommends to use `gcloud storage` commands instead of `gsutil` in Google cloud CLI.

## Slide no. 84
### Managed Services

**Suggestion:** Software as a Service (SaaS) terminology can be added.

## Slide no. 91
### GCP Managed Services for Compute

**Change:** Google Cloud is moving ***Cloud Functions*** to `Cloud Run` with the name ***Cloud Run Functions***.

## Slide no. 113
### Kubernetes - Service

Last line got cut out from the slide

## Slide no. 114
### Ingress

The last line got cut off from the slide.

## Slide no. 115
### Container Registry - Image Repository

**Change:** Google Container Registry is now **Artifact Registry**.


## Slide no. 126 to 131

-   Cloud Functions is now **Cloud Run Functions** in Cloud Run, so we need to mention it.

## Slide no. 133
### Data States

The last line got cut off from the slide.

## Slide no. 143
### GCP - Block Storage

There's new type of storage option called **Hyperdisk** available in block storage.
- The official documentation mentions: 
*Google Cloud Hyperdisk is Google's next generation block storage. By offloading and dynamically scaling out storage processing, it decouples storage performance from the VM type and size. Hyperdisk offers substantially higher performance, flexibility and efficiency when compared to Persistent Disk.*

**Source:** https://cloud.google.com/compute/docs/disks

## Slide no. 154
### Let's Compare

The comparison table has been changed. New table can be found here: 
https://cloud.google.com/compute/docs/machine-images



## Slide no. 156
### Cloud Filestore

**Change:** Firestore now also supports the NFSv4.1 protocol. In the slide, the text can be: *It supports NFSv3 as well as the NFSv4.1 protocol*.

**Source:** https://cloud.google.com/filestore/docs/about-supported-protocols


## Slide no. 156

### Review - Global, Regional and Zonal Resources

**Change :** Instance templates are now available as both  `regional` and `global` resources. 

## Slide no. 160
### Cloud Storage
**Change:** Google Cloud now recommends to use `gcloud storage` commands instead of `gsutil` in Google cloud CLI.

**Source:** https://cloud.google.com/storage/docs/gsutil

## Slide no. 165
### Object Versioning

The statement might need a revamp : Prevents accidental deletion & provides history.

**Factual error:** Objects can only be recovered from a deleted bucket when *soft delete is enabled*. Object Versioning *does not* provide protection against bucket deletions.

**Source:** https://cloud.google.com/storage/docs/object-versioning

## Slide no. 166
### Object Lifecycle Management

The last line got cut off from the slide.
## Slide no. 168
### Cloud Storage - Encryption

The last line got cut off from the slide.

## Slide no. 174
### Cloud Storage - Command Line - gsutil - 1

**Change:** Google Cloud now recommends to `gcloud storage` commands instead of `gsutil` in Google cloud CLI. The slide mentions  *(REMEMBER) gsutil is the CLI for Cloud Storage (NOT gcloud)*, which is **incorrect**.

**Source:** https://cloud.google.com/storage/docs/gsutil

## Slide no. 175
### Cloud Storage - Command Line - gsutil - 2

Same change as stated for previous slide.


## Slide no. 179
### Cloud Identity and Access Management (IAM)

The last line got cut off from the slide.

## Slide no. 195
### Cloud Storage - Static website

**Suggestion:** While stating that "the bucket name should match the DNS name for the website," it's important to specify that this is only applicable if you are using a **custom domain**. If you're using the default Google Cloud Storage domain, this requirement does not apply.

I received questions regarding this in the Udemy Q&A, so I think it will be helpful to mention it.

## Slide no. 221
### Databases - Summary

The last line got cut off from the slide.

## Slide no. 231
### Cloud Datastore and Firestore

The last line got cut off from the slide.

## Slide no. 241
### Need for VPC Subnets

**Suggestion:** We should mention that Load Balancers can also be internal.

## Slide no. 265
### Cloud Debugger 

**Change :** Cloud Debugger deprecation. Cloud Debugger was deprecated on May 16, 2022 and the service was shut down on May 31, 2023.

**Source:** https://cloud.google.com/stackdriver/docs/deprecations/debugger-deprecation


## Slide no. 267
### Error Reporting

The last line got cut off from the slide.

## Slide no. 281
### Resource Hierarchy & IAM Policy

Please review the point: "You can't restrict policy at a lower level if permission is given at a higher level," as mentioned in the slide. I read that deny policies have higher priority.

## Slide no. 283

### Corporate Directory Federation

The last line got cut off from the slide.


## Slide no. 287
### Executing Shutdown Script on a GCE VM

The last line got cut off from the slide.


## Slide no. 290
### Moving VM instances between Zones and Regions

**Change:**  This command ***gcloud compute instances move*** is deprecated.

**Source:** https://cloud.google.com/sdk/gcloud/reference/compute/instances/move

## Slide no. 302
### Cloud VPN

The last line got cut off from the slide.

## Slide no. 304
### Cloud Interconnect

The last line got cut off from the slide.

## Slide no. 313 & 314
### Importing Data into BigQuery
### Streaming Data into BigQuery

The last line got cut off from the slide.


## Slide no. 335
### Cloud CDN - Best Practices

The last line got cut off from the slide.


## Slide no. 343
### DevOps - CI, CD Tools
**Changes:**
- Cloud Source Repositories has been **deprecated**
- Container Registry is now Artifact Registry.
**Source:**  https://cloud.google.com/source-repositories/docs

## Slide no. 344
### DevOps - Infrastructure as Code

The last line got cut off from the slide.

## Slide no. 373
### PCI DSS - Other Recommendations

**Change:** The Forseti GitHub repository is archived, and it has been mentioned that there will be no additional support from Google for Forseti.

## Slide no. 389
### Planning for Scalability - 2

**Change:** Cloud Functions is now **`Cloud Run Functions`**.

## Slide no. 408
### Machine Learning in Google Cloud

**Change:** The AI Platform is no longer available; now there's **`Vertex AI`**.  
**Suggestion:** Google Cloud is promoting **`Gemini`** heavily, so we can add it to the slide.

## Slide no. 422
### Operational Excellence - Best practices

- Cloud Source Repositories has been **deprecated**.
- Container Registry is now Artifact Registry.

## Slide no. 426
### Security, Privacy and Compliance - Best practices

The last line got cut off from the slide.
