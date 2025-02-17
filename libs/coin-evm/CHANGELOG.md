# @ledgerhq/coin-evm

## 0.4.1

### Patch Changes

- [#4103](https://github.com/LedgerHQ/ledger-live/pull/4103) [`2317fccb67`](https://github.com/LedgerHQ/ledger-live/commit/2317fccb6776a077eaca8828da8371d402323be4) Thanks [@live-github-bot](https://github.com/apps/live-github-bot)! - Fix building & bundling of `evm-tools` & `domain-service` libs due to .gitignore(s)

- Updated dependencies [[`2317fccb67`](https://github.com/LedgerHQ/ledger-live/commit/2317fccb6776a077eaca8828da8371d402323be4)]:
  - @ledgerhq/evm-tools@1.0.2
  - @ledgerhq/hw-app-eth@6.34.1

## 0.4.1-hotfix.0

### Patch Changes

- [#4103](https://github.com/LedgerHQ/ledger-live/pull/4103) [`2317fccb67`](https://github.com/LedgerHQ/ledger-live/commit/2317fccb6776a077eaca8828da8371d402323be4) Thanks [@live-github-bot](https://github.com/apps/live-github-bot)! - Fix building & bundling of `evm-tools` & `domain-service` libs due to .gitignore(s)

- Updated dependencies [[`2317fccb67`](https://github.com/LedgerHQ/ledger-live/commit/2317fccb6776a077eaca8828da8371d402323be4)]:
  - @ledgerhq/evm-tools@1.0.2-hotfix.0
  - @ledgerhq/hw-app-eth@6.34.1-hotfix.0

## 0.4.0

### Minor Changes

- [#3714](https://github.com/LedgerHQ/ledger-live/pull/3714) [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Adding support for NFT transactions

- [#3786](https://github.com/LedgerHQ/ledger-live/pull/3786) [`11e62b1e1e`](https://github.com/LedgerHQ/ledger-live/commit/11e62b1e1e3773eeaad748453973e0b3bcd3e3bf) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Adds support for the `setLoadConfig` during the SignOperation step and adds the usage of environment variables to set the backends URIs

- [#3714](https://github.com/LedgerHQ/ledger-live/pull/3714) [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Add support for non finite quantity w/ NFT transaction data crafting

- [#3924](https://github.com/LedgerHQ/ledger-live/pull/3924) [`14cce73003`](https://github.com/LedgerHQ/ledger-live/commit/14cce7300333c51cbcdbd5a7e290ddc600c9f3a1) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Use of the `evm-tools` new library to bring support for SignMessage

### Patch Changes

- [#3714](https://github.com/LedgerHQ/ledger-live/pull/3714) [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Prevent duplicated sub & nft operations with rate limited explorers & make explorerless implementation also patch sub & nft operations after transaction finalization

- [#3714](https://github.com/LedgerHQ/ledger-live/pull/3714) [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Rename rpc file that prevented shims to be applied for React Native

- Updated dependencies [[`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec), [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec), [`49182846de`](https://github.com/LedgerHQ/ledger-live/commit/49182846dee35ae9b3535c0c120e17d0eaecde70), [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec), [`c660c4e389`](https://github.com/LedgerHQ/ledger-live/commit/c660c4e389ac200ef308cbc3882930d392375de3), [`2c28d5aab3`](https://github.com/LedgerHQ/ledger-live/commit/2c28d5aab36b8b0cf2cb2a50e02eac4c5a588e41), [`0f4293e9bf`](https://github.com/LedgerHQ/ledger-live/commit/0f4293e9bf9cac4c2a195efeb0831aab3d51933d), [`14cce73003`](https://github.com/LedgerHQ/ledger-live/commit/14cce7300333c51cbcdbd5a7e290ddc600c9f3a1), [`14cce73003`](https://github.com/LedgerHQ/ledger-live/commit/14cce7300333c51cbcdbd5a7e290ddc600c9f3a1), [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec), [`bae3b64dd2`](https://github.com/LedgerHQ/ledger-live/commit/bae3b64dd2710a3743552600166be986e93d9099), [`9692adc2a6`](https://github.com/LedgerHQ/ledger-live/commit/9692adc2a6774feb4424fc7a984810918c946b1b), [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec)]:
  - @ledgerhq/live-env@0.4.0
  - @ledgerhq/coin-framework@0.4.0
  - @ledgerhq/cryptoassets@9.10.0
  - @ledgerhq/errors@6.13.0
  - @ledgerhq/types-live@6.37.0
  - @ledgerhq/hw-app-eth@6.34.0
  - @ledgerhq/types-cryptoassets@7.3.1
  - @ledgerhq/evm-tools@1.0.1
  - @ledgerhq/live-network@1.1.3
  - @ledgerhq/domain-service@1.1.6
  - @ledgerhq/devices@8.0.5

## 0.4.0-next.0

### Minor Changes

- [#3714](https://github.com/LedgerHQ/ledger-live/pull/3714) [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Adding support for NFT transactions

- [#3786](https://github.com/LedgerHQ/ledger-live/pull/3786) [`11e62b1e1e`](https://github.com/LedgerHQ/ledger-live/commit/11e62b1e1e3773eeaad748453973e0b3bcd3e3bf) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Adds support for the `setLoadConfig` during the SignOperation step and adds the usage of environment variables to set the backends URIs

- [#3714](https://github.com/LedgerHQ/ledger-live/pull/3714) [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Add support for non finite quantity w/ NFT transaction data crafting

- [#3924](https://github.com/LedgerHQ/ledger-live/pull/3924) [`14cce73003`](https://github.com/LedgerHQ/ledger-live/commit/14cce7300333c51cbcdbd5a7e290ddc600c9f3a1) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Use of the `evm-tools` new library to bring support for SignMessage

### Patch Changes

- [#3714](https://github.com/LedgerHQ/ledger-live/pull/3714) [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Prevent duplicated sub & nft operations with rate limited explorers & make explorerless implementation also patch sub & nft operations after transaction finalization

- [#3714](https://github.com/LedgerHQ/ledger-live/pull/3714) [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Rename rpc file that prevented shims to be applied for React Native

- Updated dependencies [[`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec), [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec), [`49182846de`](https://github.com/LedgerHQ/ledger-live/commit/49182846dee35ae9b3535c0c120e17d0eaecde70), [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec), [`c660c4e389`](https://github.com/LedgerHQ/ledger-live/commit/c660c4e389ac200ef308cbc3882930d392375de3), [`2c28d5aab3`](https://github.com/LedgerHQ/ledger-live/commit/2c28d5aab36b8b0cf2cb2a50e02eac4c5a588e41), [`0f4293e9bf`](https://github.com/LedgerHQ/ledger-live/commit/0f4293e9bf9cac4c2a195efeb0831aab3d51933d), [`14cce73003`](https://github.com/LedgerHQ/ledger-live/commit/14cce7300333c51cbcdbd5a7e290ddc600c9f3a1), [`14cce73003`](https://github.com/LedgerHQ/ledger-live/commit/14cce7300333c51cbcdbd5a7e290ddc600c9f3a1), [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec), [`bae3b64dd2`](https://github.com/LedgerHQ/ledger-live/commit/bae3b64dd2710a3743552600166be986e93d9099), [`9692adc2a6`](https://github.com/LedgerHQ/ledger-live/commit/9692adc2a6774feb4424fc7a984810918c946b1b), [`15e8abc482`](https://github.com/LedgerHQ/ledger-live/commit/15e8abc482b2b38e4808890f556097cf693359ec)]:
  - @ledgerhq/live-env@0.4.0-next.0
  - @ledgerhq/coin-framework@0.4.0-next.0
  - @ledgerhq/cryptoassets@9.10.0-next.0
  - @ledgerhq/errors@6.13.0-next.0
  - @ledgerhq/types-live@6.37.0-next.0
  - @ledgerhq/hw-app-eth@6.34.0-next.0
  - @ledgerhq/types-cryptoassets@7.3.1-next.0
  - @ledgerhq/evm-tools@1.0.1-next.0
  - @ledgerhq/live-network@1.1.3-next.0
  - @ledgerhq/domain-service@1.1.6-next.0
  - @ledgerhq/devices@8.0.5-next.0

## 0.3.0

### Minor Changes

- [#3611](https://github.com/LedgerHQ/ledger-live/pull/3611) [`092cb8d317`](https://github.com/LedgerHQ/ledger-live/commit/092cb8d317fa7971e0f790b77f900ae3864d96c2) Thanks [@chabroA](https://github.com/chabroA)! - Create GasTracker abstraction for evm familly

### Patch Changes

- [#3741](https://github.com/LedgerHQ/ledger-live/pull/3741) [`6194db3178`](https://github.com/LedgerHQ/ledger-live/commit/6194db3178cf90b26f4f6c7f049b7eafafdf7bfc) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Update eip55 dependency

- [#3741](https://github.com/LedgerHQ/ledger-live/pull/3741) [`6194db3178`](https://github.com/LedgerHQ/ledger-live/commit/6194db3178cf90b26f4f6c7f049b7eafafdf7bfc) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Update eip55 dependency to 2.1.1 fixing browser context usage

- [#3872](https://github.com/LedgerHQ/ledger-live/pull/3872) [`d1d1578ab5`](https://github.com/LedgerHQ/ledger-live/commit/d1d1578ab5b351544c98d56b67c68f18640f2d20) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Rename rpc file that prevented shims to be applied for React Native

- Updated dependencies [[`6194db3178`](https://github.com/LedgerHQ/ledger-live/commit/6194db3178cf90b26f4f6c7f049b7eafafdf7bfc), [`44192f2ab2`](https://github.com/LedgerHQ/ledger-live/commit/44192f2ab2857cbae2ef4a81ee9608d395dcd2b9), [`cb95f72c24`](https://github.com/LedgerHQ/ledger-live/commit/cb95f72c2415876ef88ca83fd2c4363a57669b92), [`be5f56b233`](https://github.com/LedgerHQ/ledger-live/commit/be5f56b2330c166323914b79fef37a3c05e0e13a), [`092cb8d317`](https://github.com/LedgerHQ/ledger-live/commit/092cb8d317fa7971e0f790b77f900ae3864d96c2), [`5af41b6fa1`](https://github.com/LedgerHQ/ledger-live/commit/5af41b6fa1e43037ccdb2df279c82e12ef3d2b1a), [`6194db3178`](https://github.com/LedgerHQ/ledger-live/commit/6194db3178cf90b26f4f6c7f049b7eafafdf7bfc)]:
  - @ledgerhq/domain-service@1.1.5
  - @ledgerhq/types-live@6.36.0
  - @ledgerhq/cryptoassets@9.9.0
  - @ledgerhq/types-cryptoassets@7.3.0
  - @ledgerhq/live-env@0.3.1
  - @ledgerhq/hw-app-eth@6.33.7
  - @ledgerhq/coin-framework@0.3.7
  - @ledgerhq/live-network@1.1.2

## 0.3.0-next.1

### Patch Changes

- [#3872](https://github.com/LedgerHQ/ledger-live/pull/3872) [`d1d1578ab5`](https://github.com/LedgerHQ/ledger-live/commit/d1d1578ab5b351544c98d56b67c68f18640f2d20) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Rename rpc file that prevented shims to be applied for React Native

## 0.3.0-next.0

### Minor Changes

- [#3611](https://github.com/LedgerHQ/ledger-live/pull/3611) [`092cb8d317`](https://github.com/LedgerHQ/ledger-live/commit/092cb8d317fa7971e0f790b77f900ae3864d96c2) Thanks [@chabroA](https://github.com/chabroA)! - Create GasTracker abstraction for evm familly

### Patch Changes

- [#3741](https://github.com/LedgerHQ/ledger-live/pull/3741) [`6194db3178`](https://github.com/LedgerHQ/ledger-live/commit/6194db3178cf90b26f4f6c7f049b7eafafdf7bfc) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Update eip55 dependency

- [#3741](https://github.com/LedgerHQ/ledger-live/pull/3741) [`6194db3178`](https://github.com/LedgerHQ/ledger-live/commit/6194db3178cf90b26f4f6c7f049b7eafafdf7bfc) Thanks [@lambertkevin](https://github.com/lambertkevin)! - Update eip55 dependency to 2.1.1 fixing browser context usage

- Updated dependencies [[`6194db3178`](https://github.com/LedgerHQ/ledger-live/commit/6194db3178cf90b26f4f6c7f049b7eafafdf7bfc), [`44192f2ab2`](https://github.com/LedgerHQ/ledger-live/commit/44192f2ab2857cbae2ef4a81ee9608d395dcd2b9), [`cb95f72c24`](https://github.com/LedgerHQ/ledger-live/commit/cb95f72c2415876ef88ca83fd2c4363a57669b92), [`be5f56b233`](https://github.com/LedgerHQ/ledger-live/commit/be5f56b2330c166323914b79fef37a3c05e0e13a), [`092cb8d317`](https://github.com/LedgerHQ/ledger-live/commit/092cb8d317fa7971e0f790b77f900ae3864d96c2), [`5af41b6fa1`](https://github.com/LedgerHQ/ledger-live/commit/5af41b6fa1e43037ccdb2df279c82e12ef3d2b1a), [`6194db3178`](https://github.com/LedgerHQ/ledger-live/commit/6194db3178cf90b26f4f6c7f049b7eafafdf7bfc)]:
  - @ledgerhq/domain-service@1.1.5-next.0
  - @ledgerhq/types-live@6.36.0-next.0
  - @ledgerhq/cryptoassets@9.9.0-next.0
  - @ledgerhq/types-cryptoassets@7.3.0-next.0
  - @ledgerhq/live-env@0.3.1-next.0
  - @ledgerhq/hw-app-eth@6.33.7-next.0
  - @ledgerhq/coin-framework@0.3.7-next.0
  - @ledgerhq/live-network@1.1.2-next.0

## 0.2.1

### Patch Changes

- Updated dependencies [[`9adc1862dd`](https://github.com/LedgerHQ/ledger-live/commit/9adc1862dda605a722d19f3b6895bd324834c914), [`4a1454beb3`](https://github.com/LedgerHQ/ledger-live/commit/4a1454beb3f86405ba2686e07879c12a7d35ad8e), [`809065c571`](https://github.com/LedgerHQ/ledger-live/commit/809065c57198646a49adea112b9d799e35a57d25), [`d1aa522db7`](https://github.com/LedgerHQ/ledger-live/commit/d1aa522db75f7ea850efe412abaa4dc7d37af6b7), [`ebe5b07afe`](https://github.com/LedgerHQ/ledger-live/commit/ebe5b07afec441ea3e2d9103da9e1175972add47)]:
  - @ledgerhq/errors@6.12.7
  - @ledgerhq/cryptoassets@9.8.0
  - @ledgerhq/types-cryptoassets@7.2.1
  - @ledgerhq/types-live@6.35.1
  - @ledgerhq/coin-framework@0.3.6
  - @ledgerhq/domain-service@1.1.4
  - @ledgerhq/devices@8.0.4
  - @ledgerhq/hw-app-eth@6.33.6
  - @ledgerhq/live-network@1.1.1
  - @ledgerhq/live-portfolio@0.0.8

## 0.2.1-next.0

### Patch Changes

- Updated dependencies [[`9adc1862dd`](https://github.com/LedgerHQ/ledger-live/commit/9adc1862dda605a722d19f3b6895bd324834c914), [`4a1454beb3`](https://github.com/LedgerHQ/ledger-live/commit/4a1454beb3f86405ba2686e07879c12a7d35ad8e), [`809065c571`](https://github.com/LedgerHQ/ledger-live/commit/809065c57198646a49adea112b9d799e35a57d25), [`d1aa522db7`](https://github.com/LedgerHQ/ledger-live/commit/d1aa522db75f7ea850efe412abaa4dc7d37af6b7), [`ebe5b07afe`](https://github.com/LedgerHQ/ledger-live/commit/ebe5b07afec441ea3e2d9103da9e1175972add47)]:
  - @ledgerhq/errors@6.12.7-next.0
  - @ledgerhq/cryptoassets@9.8.0-next.0
  - @ledgerhq/types-cryptoassets@7.2.1-next.0
  - @ledgerhq/types-live@6.35.1-next.0
  - @ledgerhq/coin-framework@0.3.6-next.0
  - @ledgerhq/domain-service@1.1.4-next.0
  - @ledgerhq/devices@8.0.4-next.0
  - @ledgerhq/hw-app-eth@6.33.6-next.0
  - @ledgerhq/live-network@1.1.1-next.0
  - @ledgerhq/live-portfolio@0.0.8-next.0

## 0.2.0

### Minor Changes

- [#3536](https://github.com/LedgerHQ/ledger-live/pull/3536) [`a380bfc53a`](https://github.com/LedgerHQ/ledger-live/commit/a380bfc53a25bf196031337cd7ab8bc459731e16) Thanks [@chabroA](https://github.com/chabroA)! - Move evm familly logic in own package

### Patch Changes

- Updated dependencies [[`5cce6e3593`](https://github.com/LedgerHQ/ledger-live/commit/5cce6e359309110df53e16ef989c5b8b94492dfd), [`30bf4d92c7`](https://github.com/LedgerHQ/ledger-live/commit/30bf4d92c7d79cb81b1e4ad014857459739c33be), [`b30ead9d22`](https://github.com/LedgerHQ/ledger-live/commit/b30ead9d22a4bce5f8ee27febf0190fccd2ca25b), [`ce675302c7`](https://github.com/LedgerHQ/ledger-live/commit/ce675302c78311571e1087cfa35ee67580263796), [`43cdd2624c`](https://github.com/LedgerHQ/ledger-live/commit/43cdd2624cd2965ddb6e346e9a77a3cc12476500)]:
  - @ledgerhq/cryptoassets@9.7.0
  - @ledgerhq/live-network@1.1.0
  - @ledgerhq/types-live@6.35.0
  - @ledgerhq/coin-framework@0.3.5
  - @ledgerhq/domain-service@1.1.3
  - @ledgerhq/hw-app-eth@6.33.5
  - @ledgerhq/live-portfolio@0.0.7

## 0.2.0-next.1

### Patch Changes

- Updated dependencies [[`30bf4d92c7`](https://github.com/LedgerHQ/ledger-live/commit/30bf4d92c7d79cb81b1e4ad014857459739c33be)]:
  - @ledgerhq/cryptoassets@9.7.0-next.1
  - @ledgerhq/coin-framework@0.3.5-next.1
  - @ledgerhq/domain-service@1.1.3-next.1
  - @ledgerhq/hw-app-eth@6.33.5-next.1

## 0.2.0-next.0

### Minor Changes

- [#3536](https://github.com/LedgerHQ/ledger-live/pull/3536) [`a380bfc53a`](https://github.com/LedgerHQ/ledger-live/commit/a380bfc53a25bf196031337cd7ab8bc459731e16) Thanks [@chabroA](https://github.com/chabroA)! - Move evm familly logic in own package

### Patch Changes

- Updated dependencies [[`5cce6e3593`](https://github.com/LedgerHQ/ledger-live/commit/5cce6e359309110df53e16ef989c5b8b94492dfd), [`b30ead9d22`](https://github.com/LedgerHQ/ledger-live/commit/b30ead9d22a4bce5f8ee27febf0190fccd2ca25b), [`7439b63325`](https://github.com/LedgerHQ/ledger-live/commit/7439b63325a9b0181a3af4310ba787f00faa80c9), [`ce675302c7`](https://github.com/LedgerHQ/ledger-live/commit/ce675302c78311571e1087cfa35ee67580263796), [`43cdd2624c`](https://github.com/LedgerHQ/ledger-live/commit/43cdd2624cd2965ddb6e346e9a77a3cc12476500)]:
  - @ledgerhq/cryptoassets@9.7.0-next.0
  - @ledgerhq/live-network@1.1.0-next.0
  - @ledgerhq/types-live@6.35.0-next.0
  - @ledgerhq/coin-framework@0.3.5-next.0
  - @ledgerhq/domain-service@1.1.3-next.0
  - @ledgerhq/hw-app-eth@6.33.5-next.0
  - @ledgerhq/live-portfolio@0.0.7-next.0
