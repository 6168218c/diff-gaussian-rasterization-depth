# Differential Gaussian Rasterization

This is a forked repository of the rasterization pipeline from the paper "3D Gaussian Splatting for Real-Time Rendering of Radiance Fields" and "GaussianEditor: Swift and Controllable 3D Editing with Gaussian Splatting". With depth forward and backward pass added to it.

It's difference from the original gaussian-splatting diff-gaussian-rasterization is:
- applying masks for arbitrary image weights
- forward and backward pass for depth

<section class="section" id="BibTeX">
  <div class="container is-max-desktop content">
    <h2 class="title">BibTeX</h2>
    <pre><code>@Article{kerbl3Dgaussians,
      author       = {Kerbl, Bernhard and Kopanas, Georgios and Leimk{\"u}hler, Thomas and Drettakis, George},
      title        = {3D Gaussian Splatting for Real-Time Radiance Field Rendering},
      journal      = {ACM Transactions on Graphics},
      number       = {4},
      volume       = {42},
      month        = {July},
      year         = {2023},
      url          = {https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/}
}</code></pre>
  </div>
</section>