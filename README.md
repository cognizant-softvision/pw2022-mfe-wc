# Programmers' Week 2022  <br> Micro-frontends with Webpack module federation and web components

## Starting

This repo hosts submodules with separate repositories for each MFE. To initialize and pull everything correctly, run:

```git submodule update --init```  

If you want your submodules branches to be undetached, you could do:

```git submodule foreach --recursive git checkout main```

After that, go into each submodule directory and `npm i` & `npm start` as you would proceed with single project repositories.

Or run this all alogin with ```npm run init```


## Presentation

A pdf version of the presentation is available [here](https://github.com/cognizant-softvision/pw2022-mfe-wc/blob/main/pw2022-mfe-presentation.pdf)


## Additional resources

Some resources used as source for the talk and building the app.

On micro-frontends and architechture:  
https://micro-frontends.org/  
https://martinfowler.com/articles/micro-frontends.html  

Module Federation:  
[Webpack Module Federation](https://webpack.js.org/concepts/module-federation/) - oficial documentation    
[Module Federation examples](https://github.com/module-federation/module-federation-examples)  
[Module Federation + Singla Spa - Jack Herrington](https://www.youtube.com/watch?v=wxnwPLLIJCY)  
[Micro-frontend course (2hs) - Jack Herrington](https://www.youtube.com/watch?v=lKKsjpH09dU)  
[Zack Jackson's (MF creator) playlist](https://www.youtube.com/playlist?list=PLWSiF9YHHK-DqsFHGYbeAMwbd9xcZbEWJ)

Web components documentation:  
[Web Components - MDN](https://developer.mozilla.org/en-US/docs/Web/Web_Components)  
[Custom Elements Specs](https://html.spec.whatwg.org/multipage/custom-elements.html#custom-elements)
[Using Sadow DOM - MDN](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)  
https://www.webcomponents.org/

Other:  
[Import Maps - digital ocean](https://www.digitalocean.com/community/tutorials/how-to-dynamically-import-javascript-with-import-maps)  

