# MathJax Renderer Plugin for Hexo

Add support of [MathJax](http://www.mathjax.org/) for [Hexo](http://hexo.io/).

## INSTALL

    $ npm install hexo-renderer-mathjax --save

Edit `_config.yml`:

    plugins:
    - hexo-renderer-mathjax

## SAMPLE

Write the latex code:

    $$
    \frac{\partial u}{\partial t} = h^2 \left( \frac{\partial^2 u}{\partial x^2} + \frac{\partial^2 u}{\partial y^2} + \frac{\partial^2 u}{\partial z^2}\right)
    $$

And you will see:

![sample](img_url)