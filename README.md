# React Workflow Without Create React App (CRA)

## Updated November 23, 2018

### Reflects changes to React 16.6.3, Babel 7, ESLint 5.9.0, and Webpack 4.3.0

This is the second edition of a custom workflow I created for my React applications, incorporating changes that took place in React 16.6.3, ESLint 5.9.0, Babel 7, and Webpack 4. This is not meant as an all inclusive example of what has changed in those dependencies/devDependencies. Hopefully it will encourage others to take a deeper dive into them and expand their horizons as developers. I know that creating this deck expanded my horizons, and I had loads of fun learning new things along the way. To go through the first edition, please visit the <a href="https://github.com/interglobalmedia/react-workflow-presentation">React Workflow Presentation</a> repository.

If you feel that there are improvements that can be made to any of the documentation, please make a pull request and it will be reviewed for approval. Thanks!

## Site Map:

+ Landing Page: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/" target="_blank" rel="noopener noreferrer">Landing Page</a>

+ About This Presentation: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/1" target="_blank" rel="noopener noreferrer">Slide 1</a>

+ A Bit About Me: 
    + Hi There! <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/2" target="_blank" rel="noopener noreferrer">Slide 2</a> 
    + About Me <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/3" target="_blank" rel="noopener noreferrer">Slide 3</a>
    + Background <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/4" target="_blank" rel="noopener noreferrer">Slide 4</a>

+ Why Discuss React Workflows?: 
    + Why Discuss React Workflows? <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/5" target="_blank" rel="noopener noreferrer">Slide 5</a> 
    + Simple <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/6" target="_blank" rel="noopener noreferrer">Slide 6</a>
    + blindly accepting <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/7" target="_blank" rel="noopener noreferrer">Slide 7</a>
    + Why blindly? <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/8" target="_blank" rel="noopener noreferrer">Slide 8</a>
    + once you eject <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/9" target="_blank" rel="noopener noreferrer">Slide 9</a>
    + one thing I know for sure ... <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/10" target="_blank" rel="noopener noreferrer">Slide 10</a>
    + Starting Over <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/11" target="_blank" rel="noopener noreferrer">Slide 11</a>
    + Where Webpack Comes In <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/12" target="_blank" rel="noopener noreferrer">Slide 12</a>
    + So why webpack? <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/13" target="_blank" rel="noopener noreferrer">Slide 13</a>
    + If done from scratch ... <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/14" target="_blank" rel="noopener noreferrer">Slide 14</a>
    + if you are familiar with CRA ... <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/15" target="_blank" rel="noopener noreferrer">Slide 15</a>
    + Nothing wrong with that <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/16" target="_blank" rel="noopener noreferrer">Slide 16</a>
    + The Problem <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/17" target="_blank" rel="noopener noreferrer">Slide 17</a>
    + stunt one's growth <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/18" target="_blank" rel="noopener noreferrer">Slide 18</a>
    + the bug <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/19" target="_blank" rel="noopener noreferrer">Slide 19</a>
    + Debugging Difficulties <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/20" target="_blank" rel="noopener noreferrer">Slide 20</a>
+ Custom React Workflows:
    + Custom React Workflows <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/21" target="_blank" rel="noopener noreferrer">Slide 21</a>
    + What This React Workflow Supports <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/22" target="_blank" rel="noopener noreferrer">Slide 22</a>
    + What This React Workflow Uses <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/23" target="_blank" rel="noopener noreferrer">Slide 23</a>

+ package.json: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/24" target="_blank" rel="noopener noreferrer">Slide 24</a>

+ Jest:
    + What Has Not Changed (Jest): <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/25" target="_blank" rel="noopener noreferrer">Slide 25</a>
    + What Has Changed (Jest): <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/26" target="_blank" rel="noopener noreferrer">Slide 26</a>
    + What Has Not Changed (Jest DevDeps): <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/27" target="_blank" rel="noopener noreferrer">Slide 27</a>
    + What has Changed (Jest DevDeps): <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/28" target="_blank" rel="noopener noreferrer">Slide 28</a>

+ Configuring Babel 7:
    + everything changed <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/29" target="_blank" rel="noopener noreferrer">Slide 29</a>
    +  .babelrc (previously) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/30" target="_blank" rel="noopener noreferrer">Slide 30</a>
    + .babelrc (now) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/31" target="_blank" rel="noopener noreferrer">Slide 31</a>
    + Babel < 7 Presets: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/32" target="_blank" rel="noopener noreferrer">Slide 32</a>
    + Babel 7 Presets: 
        + .babelrc <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/33" target="_blank" rel="noopener noreferrer">Slide 33</a>
        + @babel/preset-env <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/34" target="_blank" rel="noopener noreferrer">Slide 34</a>
        @babel/preset-react <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/35" target="_blank" rel="noopener noreferrer">Slide 35</a>
        + naming <a hef="https://interglobalmedia.github.io/react-workflow-updated-2018/#/36" target="_blank" rel="noopener noreferrer">Slide 36</a>
    + Babel Plugins: 
        + @babel/plugin-proposal-class-properties <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/37" target="_blank" rel="noopener noreferrer">Slide 37</a>
        + @babel/plugin-proposal-export-namespace-from <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/38" target="_blank" rel="noopener noreferrer">Slide 38</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/39" target="_blank" rel="noopener noreferrer" >Slide 39</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/40" target="_blank" rel="noopener noreferrer" >Slide 40</a>
        + @babel/plugin-proposal-throw-expressions <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/41" target="_blank" rel="noopener noreferrer" >Slide 41</a>
        + babel/plugin-syntax-dynamic-import <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/42" target="_blank" rel="noopener noreferrer" >Slide 42</a>
        + config/webpack.base.config.js: 
            + JS$ rules <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/43" target="_blank" rel="noopener noreferrer" >Slide 43</a>
            + JS$ test property <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/44" target="_blank" rel="noopener noreferrer" >Slide 44</a>
            + JS$ exclude property <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/45" target="_blank" rel="noopener noreferrer" >Slide 45</a>
            + JS$ use property <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/46" target="_blank" rel="noopener noreferrer" >Slide 46</a>
    + Babel 7 Packages:
        + @babel/core <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/47" target="_blank" rel="noopener noreferrer">Slide 47</a>
        + "babel-core": "^7.0.0-bridge.0" <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/48" target="_blank" rel="noopener noreferrer">Slide 48</a>
        + @babel/polyfill <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/49" target="_blank" rel="noopener noreferrer">Slide 49</a>
        + @babel/register <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/50" target="_blank" rel="noopener noreferrer">Slide 50</a>

+ Configuring ESLint: 
    + package.json <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/51" target="_blank" rel="noopener noreferrer">Slide 51</a>
    + .eslintrc.json <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/52" target="_blank" rel="noopener noreferrer">Slide 52</a>
    + config/webpack.base.config.js <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/53" target="_blank" rel="noopener noreferrer">Slide 53</a>

+ Configuring Webpack: 
    + much changed <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/54" target="_blank" rel="noopener noreferrer">Slide 54</a>
    + config folder <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/55" target="_blank" rel="noopener noreferrer">Slide 55</a>
    + why the new configs <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/56" target="_blank" rel="noopener noreferrer">Slide 56</a>
    + what requires/variables have NOT changed (base config) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/57" target="_blank" rel="noopener noreferrer">Slide 57</a>
    + what requires/variables have changed (base config) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/58" target="_blank" rel="noopener noreferrer">Slide 58</a>
    + how module.exports has changed (base config) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/59" target="_blank" rel="noopener noreferrer">Slide 59</a>
    + config/webpack.base.config.js <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/60" target="_blank" rel="noopener noreferrer">Slide 60</a>
    + Dependency Graph <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/61" target="_blank" rel="noopener noreferrer">Slide 61</a>
    + webpack basics: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/62" target="_blank" rel="noopener noreferrer">Slide 62</a>

+ config/webpack.base.config.js: 
    + entry <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/63" target="_blank" rel="noopener noreferrer">Slide 63</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/64" target="_blank" rel="noopener noreferrer">Slide 64</a>
    + module.exports changed <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/65" target="_blank" rel="noopener noreferrer">Slide 65</a>
    + entry changed <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/66" target="_blank" rel="noopener noreferrer">Slide 66</a>
    + webpack-merge <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/67" target="_blank" rel="noopener noreferrer">Slide 67</a>
    + main <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/68" target="_blank" rel="noopener noreferrer">Slide 68</a>
    + main index.js <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/69" target="_blank" rel="noopener noreferrer">Slide 69</a>
    + core.js in index.js: <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/70" target="_blank" rel="noopener noreferrer">Slide 70</a>
    + ReactDOM.render() <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/71" target="_blank" rel="noopener noreferrer">Slide 71</a>
    + Code/Bundle Splitting <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/72" target="_blank" rel="noopener noreferrer">Slide 72</a>
    + Browser Caching <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/73" target="_blank" rel="noopener noreferrer">Slide 73</a>
    + Clearing The Cache <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/74" target="_blank" rel="noopener noreferrer">Slide 74</a>
    + Caching Headaches <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/75" target="_blank" rel="noopener noreferrer">Slide 75</a>
    + Output <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/76" target="_blank" rel="noopener noreferrer">Slide 76</a>
    + filename <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/77" target="_blank" rel="noopener noreferrer">Slide 77</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/78" target="_blank" rel="noopener noreferrer">Slide 78</a>
    + chunkFilename <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/79" target="_blank" rel="noopener noreferrer">Slide 79</a>
    + path <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/80" target="_blank" rel="noopener noreferrer">Slide 80</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/81" target="_blank" rel="noopener noreferrer">Slide 81</a>
    + [name] <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/82" target="_blank" rel="noopener noreferrer">Slide 82</a>
    + Bundle Splitting vs Code Splitting <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/83" target="_blank" rel="noopener noreferrer">Slide 83</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/84" target="_blank" rel="noopener noreferrer">Slide 84</a>
    + [name] <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/85" target="_blank" rel="noopener noreferrer">Slide 85</a>
    + [contenthash] <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/86" target="_blank" rel="noopener noreferrer">Slide 86</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/87" target="_blank" rel="noopener noreferrer">Slide 87</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/88" target="_blank" rel="noopener noreferrer">Slide 88</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/89" target="_blank" rel="noopener noreferrer">Slide 89</a>
    + < /> === 3 <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/90" target="_blank" rel="noopener noreferrer">Slide 90</a>
    + Runtime <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/91" target="_blank" rel="noopener noreferrer">Slide 91</a>
    + Manifest <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/92" target="_blank" rel="noopener noreferrer">Slide 92</a>
    + Runtime/Manifest <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/93" target="_blank" rel="noopener noreferrer">Slide 93</a>
    + Side Effects <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/94" target="_blank" rel="noopener noreferrer">Slide 94</a>
    + [chunkhash] <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/95" target="_blank" rel="noopener noreferrer">Slide 95</a>
    + CommonsChunkPlugin <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/96" target="_blank" rel="noopener noreferrer">Slide 96</a>
    + SplitChunksPlugin <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/97" target="_blank" rel="noopener noreferrer">Slide 97</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/98" target="_blank" rel="noopener noreferrer">Slide 98</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/99" target="_blank" rel="noopener noreferrer">Slide 99</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/100" target="_blank" rel="noopener noreferrer">Slide 100</a>
    + (SplitChunksPlugin) Conditions <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/101" target="_blank" rel="noopener noreferrer">Slide 101</a>
    + Extracting a Runtime <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/102" target="_blank" rel="noopener noreferrer">Slide 102</a>
    + Dev Output In Terminal <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/103" target="_blank" rel="noopener noreferrer">Slide 103</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/104" target="_blank" rel="noopener noreferrer">Slide 104</a>
    + custom script, webpack-dev-server: 
        + (npm run start) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/105" target="_blank" rel="noopener noreferrer">Slide 105</a>
            + --mode development <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/106" target="_blank" rel="noopener noreferrer">Slide 106</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/107" target="_blank" rel="noopener noreferrer">Slide 107</a>
        + custom script, webpack-dev-server <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/108" target="_blank" rel="noopener noreferrer">Slide 108</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/109" target="_blank" rel="noopener noreferrer">Slide 109</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/110" target="_blank" rel="noopener noreferrer">Slide 110</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/111" target="_blank" rel="noopener noreferrer">Slide 111</a>
            + style-loader <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/112" target="_blank" rel="noopener noreferrer">Slide 112</a>
            + --history-api-fallback <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/113" target="_blank" rel="noopener noreferrer">Slide 113</a>
            + --env.PLATFORM=local <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/114" target="_blank" rel="noopener noreferrer">Slide 114</a>
            + --env.VERSION=stag <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/115" target="_blank" rel="noopener noreferrer">Slide 115</a>
        + Dev Output In Terminal: 
            + dev instance info:
                + clean-webpack-plugin <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/116" target="_blank" rel="noopener noreferrer">Slide 116</a>
                + [wds] <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/117" target="_blank" rel="noopener noreferrer">Slide 117</a>
                + --history-api-fallback <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/118" target="_blank" rel="noopener noreferrer">Slide 118</a>
                + [wdm] <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/119" target="_blank" rel="noopener noreferrer">Slide 119</a>
                [wds]/[wdm] <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/120" target="_blank" rel="noopener noreferrer">Slide 120</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/121" target="_blank" rel="noopener noreferrer">Slide 121</a>
                [wdm] (when change is made to dev build) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/122" target="_blank" rel="noopener noreferrer">Slide 122</a>
            + dev instance info <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/123" target="_blank" rel="noopener noreferrer">Slide 123</a>
            + assets emitted <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/124" target="_blank" rel="noopener noreferrer">Slide 124</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/125" target="_blank" rel="noopener noreferrer">Slide 125</a>
            + other webpack base configs:
                + (optimization.splitChunks.chunks) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/126" target="_blank" rel="noopener noreferrer">Slide 126</a>
                + CopyWebpackPlugin <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/127" target="_blank" rel="noopener noreferrer">Slide 127</a>
                + WorkboxPlugin <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/128" target="_blank" rel="noopener noreferrer">Slide 128</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/129" target="_blank" rel="noopener noreferrer">Slide 129</a>
                + service worker (precache files) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/130" target="_blank" rel="noopener noreferrer">Slide 130</a>
                + workbox and precaching <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/131" target="_blank" rel="noopener noreferrer">Slide 131</a>
                + precache-manifest.json <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/132" target="_blank" rel="noopener noreferrer">Slide 132</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/133" target="_blank" rel="noopener noreferrer">Slide 133</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/134" target="_blank" rel="noopener noreferrer">Slide 134</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/135" target="_blank" rel="noopener noreferrer">Slide 135</a>

        + Build Output in Terminal <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/136" target="_blank" rel="noopener noreferrer">Slide 136</a>
            + custom script, npm run predeploy <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/137" target="_blank" rel="noopener noreferrer">Slide 137</a>
            + --mode production <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/138" target="_blank" rel="noopener noreferrer">Slide 138</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/139" target="_blank" rel="noopener noreferrer">Slide 139</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/140" target="_blank" rel="noopener noreferrer">Slide 140</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/141" target="_blank" rel="noopener noreferrer">Slide 141</a>
            + assets emitted <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/142" target="_blank" rel="noopener noreferrer">Slide 142</a>
            + assets emitted: bundle splitting <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/143" target="_blank" rel="noopener noreferrer">Slide 143</a>
+ config/webpack.prod.config.js <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/144" target="_blank" rel="noopener noreferrer">Slide 144</a>

    + Build Output In Terminal:
        + (vendor) node_module bundle splitting <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/145" target="_blank" rel="noopener noreferrer">Slide 145</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/146" target="_blank" rel="noopener noreferrer">Slide 146</a>
    + Build Output In Terminal:
        + (vendor) bundle splitting <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/147" target="_blank" rel="noopener noreferrer">Slide 147</a>
+ webpack.prod.config.js:
    + what hasn't changed <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/148" target="_blank" rel="noopener noreferrer">Slide 148</a>
    + what's new <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/149" target="_blank" rel="noopener noreferrer">Slide 149</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/150" target="_blank" rel="noopener noreferrer">Slide 150</a>
    + prodConfiguration <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/151" target="_blank" rel="noopener noreferrer">Slide 151</a>
    + merge() <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/152" target="_blank" rel="noopener noreferrer">Slide 152</a>
    + optimization <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/153" target="_blank" rel="noopener noreferrer">Slide 153</a>
    + splitChunks <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/154" target="_blank" rel="noopener noreferrer">Slide 154</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/155" target="_blank" rel="noopener noreferrer">Slide 155</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/156" target="_blank" rel="noopener noreferrer">Slide 156</a>
    + cacheGroups <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/157" target="_blank" rel="noopener noreferrer">Slide 157</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/158" target="_blank" rel="noopener noreferrer">Slide 158</a>
    + Configuring cacheGroups: vendor <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/159" target="_blank" rel="noopener noreferrer">Slide 159</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/160" target="_blank" rel="noopener noreferrer">Slide 160</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/161" target="_blank" rel="noopener noreferrer">Slide 161</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/162" target="_blank" rel="noopener noreferrer">Slide 162</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/163" target="_blank" rel="noopener noreferrer">Slide 163</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/164" target="_blank" rel="noopener noreferrer">Slide 164</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/165" target="_blank" rel="noopener noreferrer">Slide 165</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/166" target="_blank" rel="noopener noreferrer">Slide 166</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/167" target="_blank" rel="noopener noreferrer">Slide 167</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/168" target="_blank" rel="noopener noreferrer">Slide 168</a>
    + cacheGroups: styles <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/169" target="_blank" rel="noopener noreferrer">Slide 169</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/170" target="_blank" rel="noopener noreferrer">Slide 170</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/171" target="_blank" rel="noopener noreferrer">Slide 171</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/172" target="_blank" rel="noopener noreferrer">Slide 172</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/173" target="_blank" rel="noopener noreferrer">Slide 173</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/174" target="_blank" rel="noopener noreferrer">Slide 174</a>
    + optimization: runtimeChunk <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/175" target="_blank" rel="noopener noreferrer">Slide 175</a>
    + optimization: minimizer <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/176" target="_blank" rel="noopener noreferrer">Slide 176</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/177" target="_blank" rel="noopener noreferrer">Slide 177</a>
    + plugins <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/178" target="_blank" rel="noopener noreferrer">Slide 178</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/179" target="_blank" rel="noopener noreferrer">Slide 179</a>
    + asset-manifest.json <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/180" target="_blank" rel="noopener noreferrer">Slide 180</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/181" target="_blank" rel="noopener noreferrer">Slide 181</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/182" target="_blank" rel="noopener noreferrer">Slide 182</a>
    + HashedModuleIdsPlugin <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/183" target="_blank" rel="noopener noreferrer">Slide 183</a>
    + Publishing to gh-pages on Build <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/184" target="_blank" rel="noopener noreferrer">Slide 184</a>
    + Separating Concerns <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/185" target="_blank" rel="noopener noreferrer">Slide 185</a>
    + HtmlWebpackPlugin <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/186" target="_blank" rel="noopener noreferrer">Slide 186</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/187" target="_blank" rel="noopener noreferrer">Slide 187</a>
    + HtmlWebpackPlugin Configuration:
        + template <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/188" target="_blank" rel="noopener noreferrer">Slide 188</a>
        + favicon <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/189" target="_blank" rel="noopener noreferrer">Slide 189</a>
        + styles <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/190" target="_blank" rel="noopener noreferrer">Slide 190</a>
        + inject <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/191" target="_blank" rel="noopener noreferrer">Slide 191</a>
    + Separating Concerns (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/192" target="_blank" rel="noopener noreferrer">Slide 192</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/193" target="_blank" rel="noopener noreferrer">Slide 193</a>
    + Resolving Order <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/194" target="_blank" rel="noopener noreferrer">Slide 194</a>
    + Blocking Change <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/195" target="_blank" rel="noopener noreferrer">Slide 195</a>
    + Named Modules Plugin <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/196" target="_blank" rel="noopener noreferrer">Slide 196</a>
    + HashedModuleIdsPlugin (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/197" target="_blank" rel="noopener noreferrer">Slide 197</a>
    + HashedModuleIdsPlugin (before) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/198" target="_blank" rel="noopener noreferrer">Slide 198</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/199" target="_blank" rel="noopener noreferrer">Slide 199</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/200" target="_blank" rel="noopener noreferrer">Slide 200</a>
    + HashedModuleIdsPlugin (after) 
        + Vendor remains constant <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/201" target="_blank" rel="noopener noreferrer">Slide 201</a>
    + Loaders (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/202" target="_blank" rel="noopener noreferrer">Slide 202</a>
    + MiniCssExtractPlugin (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/203" target="_blank" rel="noopener noreferrer">Slide 203</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/204" target="_blank" rel="noopener noreferrer">Slide 204</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/205" target="_blank" rel="noopener noreferrer">Slide 205</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/206" target="_blank" rel="noopener noreferrer">Slide 206</a>
    + vs ExtractTextWebpackPlugin (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/207" target="_blank" rel="noopener noreferrer">Slide 207</a>
    + MiniCssExtractPlugin (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/208" target="_blank" rel="noopener noreferrer">Slide 208</a>
    + MiniCssExtractPlugin (prod config) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/209" target="_blank" rel="noopener noreferrer">Slide 209</a>
        + CSS test property <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/210" target="_blank" rel="noopener noreferrer">Slide 210</a>
        + CSS exclude property <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/211" target="_blank" rel="noopener noreferrer">Slide 211</a>
        + MiniCssExtractPlugin.loader <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/212" target="_blank" rel="noopener noreferrer">Slide 212</a>
        + CSS Loader and CSS Modules <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/213" target="_blank" rel="noopener noreferrer">Slide 213</a>
        + CSS Modules <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/214" target="_blank" rel="noopener noreferrer">Slide 214</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/215" target="_blank" rel="noopener noreferrer">Slide 215</a>
        + SCSS, CSS Modules, and React <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/216" target="_blank" rel="noopener noreferrer">Slide 216</a>
        + css hot loader <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/217" target="_blank" rel="noopener noreferrer">Slide 217</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/218" target="_blank" rel="noopener noreferrer">Slide 218</a>
        + Hot Module Replacement <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/219" target="_blank" rel="noopener noreferrer">Slide 219</a>
        + [contenthash] (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/220" target="_blank" rel="noopener noreferrer">Slide 220</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/221" target="_blank" rel="noopener noreferrer">Slide 221</a>
        + Plugins (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/222" target="_blank" rel="noopener noreferrer">Slide 222</a>
        + Require (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/223" target="_blank" rel="noopener noreferrer">Slide 223</a>
        + Add <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/224" target="_blank" rel="noopener noreferrer">Slide 224</a>
        + CRA approach <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/225" target="_blank" rel="noopener noreferrer">Slide 225</a>
        + Custom NPM Scripts (recap) <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/226" target="_blank" rel="noopener noreferrer">Slide 226</a>
            + clean script <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/227" target="_blank" rel="noopener noreferrer">Slide 227</a>
            + cleanSrc script <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/228" target="_blank" rel="noopener noreferrer">Slide 228</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/229" target="_blank" rel="noopener noreferrer">Slide 229</a>
        + POSTCSS <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/230" target="_blank" rel="noopener noreferrer">Slide 230</a>
        + Wrap Up <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/231" target="_blank" rel="noopener noreferrer">Slide 231</a>
        + CRA <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/232" target="_blank" rel="noopener noreferrer">Slide 232</a>
        + Custom React App - Amido <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/233" target="_blank" rel="noopener noreferrer">Slide 233</a>
        + React <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/234" target="_blank" rel="noopener noreferrer">Slide 234</a>
        + React DevTools <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/235" target="_blank" rel="noopener noreferrer">Slide 235</a>
        + webpack <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/236" target="_blank" rel="noopener noreferrer">Slide 236</a>
        + Resources <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/237" target="_blank" rel="noopener noreferrer">Slide 237</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/238" target="_blank" rel="noopener noreferrer">Slide 238</a>, <a href="https://interglobalmedia.github.io/react-workflow-updated-2018/#/239" target="_blank" rel="noopener noreferrer">Slide 239</a>




