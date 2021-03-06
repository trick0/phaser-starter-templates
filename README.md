# Phaser Starter Templates
This repository includes a number of starter templates for [Phaser][phaser] game framework, and was originally part of my [Phaser Tutorials collection](https://github.com/JamesSkemp/PhaserTutorials).

## Templates
All templates use [Visual Studio Code][vs-code], but do not require that it be used. However, Visual Studio Code is a great, free, cross-platform application, and is highly recommended.

[TypeScript][typescript] is used, and required, for all templates. Some templates use [Node.js][node-js].

See each individual project for specific requirements and setup instructions.

### Phaser Community Edition
As of this writing, Phaser Community Edition (CE) is the active branch of Phaser v2. New features and bug fixes are being made to this code, so it's recommended to use this.

- [Starter Project for Phaser CE with Visual Studio Code, TypeScript, and NodeJS](./v2-ce/_starter-v2-ce-vsc-ts-node): Recommended for new development, uses NodeJS for pulling Phaser CE.
- [Starter Project for Phaser CE with Visual Studio Code and TypeScript](./v2-ce/_starter-v2-ce-vsc-ts): The same as the above project, but Phaser CE must be manually updated by grabbing the code from the [Phaser site][phaser].

### Phaser 2.6.2
Version 2.6.2 was the last official/non-community edition of Phaser. While this version can be used, it is no longer actively supported.

- [Starter Project for Phaser with Visual Studio Code and TypeScript](./v2-official/_starter-v2-vsc-ts): Uses the last official release of Phaser 2.

### Phaser 3
Phaser 3 (previously named Lazer) is the latest official version of Phaser.

- [Starter Project for Phaser with Visual Studio Code and TypeScript](./v3/_starter-v3-vsc-ts-node): Uses NodeJS for pulling Phaser 3. TypeScript definitions are manually updated, as they are not yet part of the npm process.

## Phaser Logo Usage
The Phaser logo (Phaser-Logo-Small.png) is a trademark of Photon Storm, and is meant to be used in a manner consistent with their [usage guidelines](https://phaser.io/download/trademark).

[phaser]: https://phaser.io/
[vs-code]: https://code.visualstudio.com/
[typescript]: https://www.typescriptlang.org/
[node-js]: https://nodejs.org/en/
