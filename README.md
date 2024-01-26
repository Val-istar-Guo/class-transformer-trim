# @miaooo/class-transformer-trim

[![version](https://img.shields.io/npm/v/@miaooo/class-transformer-trim.svg?style=flat-square)](https://www.npmjs.com/package/@miaooo/class-transformer-trim)
[![downloads](https://img.shields.io/npm/dm/@miaooo/class-transformer-trim.svg?style=flat-square)](https://www.npmjs.com/package/@miaooo/class-transformer-trim)
[![license](https://img.shields.io/npm/l/@miaooo/class-transformer-trim.svg?style=flat-square)](https://www.npmjs.com/package/@miaooo/class-transformer-trim)
[![dependencies](https://img.shields.io/david/Val-istar-Guo/class-transformer-trim.svg?style=flat-square)](https://www.npmjs.com/package/@miaooo/class-transformer-trim)
[![coveralls](https://img.shields.io/coveralls/github/Val-istar-Guo/class-transformer-trim.svg?style=flat-square)](https://coveralls.io/github/Val-istar-Guo/class-transformer-trim)

> **DEPRECATED**
>
> **This package has been deprecated. Please use** [**@buka/class-transformer-extra**](https://www.npmjs.com/package/@buka/class-transformer-extra) **instead**.

<!-- description -->

A class transformer helper that trim the string.

<!-- description -->

## Usage

<!-- usage -->

```typescript
import { Trim } from '@miaooo/class-transformer-trim';

// my.dto.ts
export MyDTO {
  @ApiProperty({ type: 'string' })
  @Trim()
  name: string;
}
```

<!-- usage -->

<!-- addition -->
<!-- addition -->

## Contributing & Development

If there is any doubt, it is very welcome to discuss the issue together.
Please read [Contributor Covenant Code of Conduct](.github/CODE_OF_CONDUCT.md) and [CONTRIBUTING](.github/CONTRIBUTING.md).
