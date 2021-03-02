---
title: Deploy in Mainland of China
category: CN
position: 1000
badge: Beta
---

## China

For user who want to deploy your own projects in the mainland of China, please contact <contact@let.sh> to enable certain feature beta program.

## Domains

### let.sh Domains

The global domain [let.sh](let.sh) not available for deployments to global, the users in mainland of China will visit servers outside the mainland of China. If you want to deploy service to mainland of China and entered the beta program, please use [let.sh.cn](let.sh.cn).

### Custom Domains

<alert type="warning">

Please ensure your custom domain already finshed the [ICP Registration](https://en.wikipedia.org/wiki/ICP_license) under the [Tencent Cloud](https://intl.cloud.tencent.com)

</alert>

The dns cname source for mainland of China service are different. Once you have enable the ability to deploy in mainland of China, please use `cn.oasis.name` as your cname source.

## Projects

The deployments under the same project are separate for the global and the cn domains. For example, if you didn‘t specify the deployment location, it will deploy to the global domains by default, you will need to deploy again with `--cn` flag if you want to deploy to the domain in the mainland of China again.
