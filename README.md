# sqr, the square code generator

> sqr, pronounced "square", is a web-based 2D code generator that just works and is stupidly simple to use.  
> Every code (QRCode, Datamatrix, Aztec, ..) is generated fully client-side and with the data you provided.  
> It is free, open-source and does not track you in any way. The data you entered is the one you scan!

## Rationale

A few years ago, it was easy to find a QR Code generator online, that would just work and not try to 
inject their own URL for tracking or just to monetize, what should have worked as a simple tool.
Nowadays, it is quite hard to find good code generators that are free, with some kinds of cosmetic option,
and that just work.

This project is an attempt to bring back a simple, free and open-source code generator that just works, 
but while I am at it, I could learn a thing or two about what is going on under the hood of these codes, 
and how to generate them.

## Under the hood

Web-app is based on [SolidJS](https://www.solidjs.com/) and [Vite](https://vitejs.dev/).
Since it is fully client-side and static app, it can be hosted anywhere, like on GitHub Pages.

Test it yourself at [https://sqr.fusetim.space](https://sqr.fusetim.space).

### Dev, build and run

As a vite project, you can run the following commands:

```bash
# install dependencies
npm install
npm run dev # run the dev server
npm run build # build the project
```

## License and contributions

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Feel free to run it, redistribute it or contribute back by opening issues or submitting pull requests.

*Please note, that the original license file MUST be included in any redistribution of this project, 
as it is a requirement of the license. We also appreciate if you mention the original project in your redistribution.*