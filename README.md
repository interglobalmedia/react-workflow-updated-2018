# React Workflow Without Create React App (CRA)

## Updated November 23, 2018

### Reflects changes to React 16.6.3, Babel 7, ESLint 5.9.0, and Webpack 4.3.0

This is the second edition of a custom workflow I created for my React applications, incorporating changes that took place in React 16.6.3, ESLint 5.9.0, Babel 7, and Webpack 4. This is not meant as an all inclusive example of what has changed in those dependencies/devDependencies. Hopefully it will encourage others to take a deeper dive into them and expand their horizons as developers. I know that creating this deck expanded my horizons, and I had loads of fun learning new things along the way. To go through the first edition, please visit the <a href="https://github.com/interglobalmedia/react-workflow-presentation">React Workflow Presentation</a> repository.

If you feel that there are improvements that can be made to any of the documentation, please make a pull request and it will be reviewed for approval. Thanks!

## Site Map:

+ Landing Page: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/" target="_blank" rel="noopener noreferrer">Landing Page</a>

+ About This Presentation: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/1" target="_blank" rel="noopener noreferrer">Slide 1</a>

+ A Bit About Me: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/2" target="_blank" rel="noopener noreferrer">Slide 2</a> - <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/4" target="_blank" rel="noopener noreferrer">Slide 4</a>

+ Why Discuss React Workflows?: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/5" target="_blank" rel="noopener noreferrer">Slide 5</a> - <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/11" target="_blank" rel="noopener noreferrer">Slide 11</a>

+ Where Webpack Comes In: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/12" target="_blank" rel="noopener noreferrer">Slide 12</a> - <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/20" target="_blank" rel="noopener noreferrer">Slide 20</a>

+ Custom React Workflows: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/21" target="_blank" rel="noopener noreferrer">Slide 21</a> - <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/23" target="_blank" rel="noopener noreferrer">Slide 23</a>

+ package.json: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/24" target="_blank" rel="noopener noreferrer">Slide 24</a>

+ What Has Not Changed (Jest): <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/25" target="_blank" rel="noopener noreferrer">Slide 25</a>

+ What Has Changed (Jest): <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/26" target="_blank" rel="noopener noreferrer">Slide 26</a>

+ What Has Not Changed (Jest DevDeps): <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/27" target="_blank" rel="noopener noreferrer">Slide 27</a>

+ What has Changed (Jest DevDeps): <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/28" target="_blank" rel="noopener noreferrer">Slide 28</a>

+ Configuring Babel 7: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/29" target="_blank" rel="noopener noreferrer">Slide 29</a> -  <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/31" target="_blank" rel="noopener noreferrer">Slide 31</a>

+ Babel < 7 Presets: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/32" target="_blank" rel="noopener noreferrer">Slide 32</a>

+ Babel 7 Presets: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/33" target="_blank" rel="noopener noreferrer">Slide 33</a> - <a hef="https://interglobalmedia.github.io/react-workflow-updated-2018/#/36" target="_blank" rel="noopener noreferrer">Slide 36</a>

+ Babel Plugins: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/37" target="_blank" rel="noopener noreferrer">Slide 37</a> - <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/42" target="_blank" rel="noopener noreferrer">Slide 42</a>

+ Configuring Babel 7 (config/webpack.base.config.js): <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/43" target="_blank" rel="noopener noreferrer">Slide 43</a>

+ JS$ test property: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/44" target="_blank" rel="noopener noreferrer">Slide 44</a>

+ JS$ exclude property:
 <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/45" target="_blank" rel="noopener noreferrer">Slide 45</a>

+ JS$ use property:
<a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/46" target="_blank" rel="noopener noreferrer">Slide 46</a>

+ Babel 7 Packages:
<a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/47" target="_blank" rel="noopener noreferrer">Slide 47</a> - <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/50" target="_blank" rel="noopener noreferrer">Slide 50</a>

+ Configuring ESLint: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/51" target="_blank" rel="noopener noreferrer">Slide 51</a> - <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/50" target="_blank" rel="noopener noreferrer">Slide 53</a>

+ Configuring Webpack: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/54" target="_blank" rel="noopener noreferrer">Slide 54</a> - <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/60" target="_blank" rel="noopener noreferrer">Slide 60</a>

+ Dependency Graph: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/61" target="_blank" rel="noopener noreferrer">Slide 61</a>

+ webpack basics: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/62" target="_blank" rel="noopener noreferrer">Slide 62</a>

+ entry: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/63" target="_blank" rel="noopener noreferrer">Slide 63</a> - <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/64" target="_blank" rel="noopener noreferrer">Slide 64</a>

+ Configuring Webpack:
    + + module.exports changed <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/65" target="_blank" rel="noopener noreferrer">Slide 65</a>
    + + entry changed <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/66" target="_blank" rel="noopener noreferrer">Slide 66</a>
    + + webpack-merge <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/67" target="_blank" rel="noopener noreferrer">Slide 67</a>
    + + main <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/68" target="_blank" rel="noopener noreferrer">Slide 68</a>
    + + main index.js <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/69" target="_blank" rel="noopener noreferrer">Slide 69</a>
    + + core.js in index.js: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/70" target="_blank" rel="noopener noreferrer">Slide 70</a>
    + + ReactDOM.render() <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/71" target="_blank" rel="noopener noreferrer">Slide 71</a>
    + + Code/Bundle Splitting <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/72" target="_blank" rel="noopener noreferrer">Slide 72</a>
    + + Browser Caching



