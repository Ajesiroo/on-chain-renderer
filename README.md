# On-chain renderer

Service worker that allows you to render pages from my blog stored on Ethereum layer 2 (Optimism) directly in the browser.

It's a fork of the more extensive project by `numtel` that’s been stripped down to the bare essentials needed to retrieve and display content stored on-chain.

## Installation

```
$ git clone https://github.com/Ajesiroo/on-chain-renderer.git
$ cd on-chain-renderer
$ npm install
```

## Usage

After starting the server using `npm run serve`, navigate to the browser and append the full path to the URL, for instance, `http://localhost:3000/0x.../ExamplePage.html`.

The following pages are available from the blog. More will likely be added later as additional pages are moved on-chain.

| Page Name | Path |
| --- | --- |
| Against decentralism | `/0x5f90D8B4918741119362446Ffe48B576F8F7faef/against-decentralism.html` |

## License

MIT