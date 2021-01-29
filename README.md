# Packer AWS Example

## Usage

`var-aws.json` 파일을 자신의 환경에 맞게 준비한다.

### Build Apache HTTPD Image

```bash
packer build -var-file=var-aws.json -var-file=var-apache.json packer.json
```

### Build MariaDB Image

```bash
packer build -var-file=var-aws.json -var-file=var-mariadb.json packer.json
```
