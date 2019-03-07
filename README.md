# Baseline
Packer script to build up a new baseline AMI for use as our EBS instances and then further hardened.
This is a step in achieving uniformity and stanard OS security practices. The hardening is done according to CIS benchmarking.



#Usage

```bash
packer validate -var 'aws_access_key=your_key' -var 'aws_secret_key=your_secret' basestack.json
```

```bash
packer build -var 'aws_access_key=your_key' -var 'aws_secret_key=your_secret' basestack.json 
```



