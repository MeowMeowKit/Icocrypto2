# ICO Crypto
This is a landing page theme written in NextJS Typescript which allows writing content and configuring pages though [mdx files](https://blog.jetbrains.com/webstorm/2021/10/building-a-blog-with-next-js-and-mdx/). The production landing page will be deployed as [static generation](https://nextjs.org/docs/basic-features/pages#static-generation-recommended).
## Development
Source codes will be placed under "src" directory, especially pages code will be placed at "src/pages" directory. In case of a project using this theme, write its own pages under "pages" directory then all "src/pages" will be ignored. In the other hand, all source codes  must pass the static generation phase:
```
npm run export
```
## License
Copyright &copy; 2022 [Hieu Pham](https://github.com/hieupth). All rights reserved.