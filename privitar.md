# Enterprise Data Privacy Platform


## Tune De-Identification

### 1. Tokenization
1. Enable Consistency & Linkability
1. Preserve Format
1. **Re-Identify Data** - Privitar lets you decide when tokenized data can be reversed

### 2. Encryption
1. Privitar supports 256-bit encryption.
1. You own the keys; **Privitar does not manage the keys.** That way they are safe and secure using your standard systems and processes.


꺅 그럼 키 관리는 내가 해야된다는 거자나? :0
---

### 3. Generalization - 단순한 binning 이라고 생각했는데 그게 아닌겨~~
1. Apply K-Anonymity  
_to Protect Against Data Linkage_  
>  K-Anonymity : every individual in a dataset is indistinguishable from at least k-1 others.  
> ![kanonymity_k3](./images/kanonymity_k3.png)  

1. Maintain Control  
_with Manual Generalization_
1. Maximize Utility  
_with Automatic Generalization_
   1. define k-anonymity cluster size  
   1.  allow the Privitar Platform to dynamically determine the generalization rules to use  

### 4. Masking ( ≄ Pseudonymization and Tokenization )

### 5. Perturbation ; 인자변환
규정된 일반화 수준 이내에서, 각 개인에 대해 일관된 방식으로 특정한 값을 다른 값으로 교체할 수 있다. 
예를 들면, 모든 연령을 원래 연령의 (-2 ... 2)년으로 임의로 조정하거나 또는 입원 또는 퇴원 일자를 체계적으로 같은 일자로 (-1000 ... 1000)일을 이동시킬 수 있다.

### 6. Redaction

### 7. Substitution

<br>

<img src="./images/privitar_unmask.png" alt="Drawing" style="width: 500px;"/>

<br>

## Apply Consistent Privacy Policies

### 1. Decouple _Privacy Policy Management_ from Implementation

### 2. Manage Your Policies from the UI or REST APIs
1. easy-to-use Privitar Policy Manager UI
1. Automation at Scale
   1. Scale-up Data Provisioning via Automation
   1. Automate De-Identification with Privitar’s REST APIs
   1. Deliver Privacy as a Service with Privitar On Demand
   1. Achieve an End-to-End Integrated Data Pipeline
      1. Metadata imported from tools, such as _data discovery_ , _data catalogs_ , and _identity and access management (IAM)_ , can be used to determine the appropriate Privacy Policies
      1. metadata from **Privitar Protected Data Domains™** can be **synced back** to these systems and used to enforce correct data usage and data expiration in accordance with your standards and policies
   1. Monitor and Audit Your Automated Processes

### 3. Centralize or Distribute Policy Creation

<br>

<img src="./images/privitar_policies.png" alt="Drawing" style="width: 600px;"/>

<br>

## Trace Data Provenance

### 1. Uniquely Identify Protected Data

### 2. Identity Travels with Each Dataset

### 3. Track and Control Data Movement

### 4. Difficult To Defeat by Design

### 5. Reduce Insider Threats

### 6. Accelerate Breach Notification and Remediation


<br>

<img src="./images/privitar_watermark.png" alt="Drawing" style="width: 500px;"/>

<br>
