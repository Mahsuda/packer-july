Clone Repo
cd tools
packer validate -var-file=../configuration/region/region/eu-west-1/eu-west-1.json golden_image.json
packer build -var-file=../configuration/region/region/eu-west-1/eu-west-1.json golden_image.json