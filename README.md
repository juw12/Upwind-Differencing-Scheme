<!-- HERO:START -->
<p align="center">
  <a href="https://github.com/juw12/Upwind-Differencing-Scheme"><img src="docs/media/banner.jpg" alt="Upwind Differencing Scheme: First-order upwind differencing for 1-D wave propagation." width="100%"></a>
</p>

<p align="center">
  <b>First-order upwind differencing for 1-D wave propagation.</b><br>
  A computational fluid dynamics study of upwind differencing, with plotted results.
</p>

<p align="center">
  <a href="#see-it-in-action">See it in action</a> ·
  <a href="#highlights">Highlights</a> ·
  <a href="https://github.com/juw12">More by juw12</a>
</p>

<p align="center">
  <a href="https://github.com/juw12/Upwind-Differencing-Scheme"><img src="https://img.shields.io/github/last-commit/juw12/Upwind-Differencing-Scheme?label=updated&color=0891b2" alt="Last updated"></a>
  <img src="https://img.shields.io/badge/CFD-24292f" alt="CFD">
  <img src="https://img.shields.io/badge/Gnuplot-24292f" alt="Gnuplot">
</p>

<a id="highlights"></a>
<table>
  <tr>
    <td width="33%" valign="top">
      <b>Upwind differencing</b><br>
      A first-order explicit scheme for the 1-D wave equation.
    </td>
    <td width="33%" valign="top">
      <b>Plotted results</b><br>
      Solutions at several time levels, plotted with Gnuplot.
    </td>
    <td width="33%" valign="top">
      <b>Compare schemes</b><br>
      Pairs with the Explicit MacCormack study.
    </td>
  </tr>
</table>

## See it in action

<p align="center">
  <a href="https://github.com/juw12/Upwind-Differencing-Scheme"><img src="upwind_1_5_10.png" alt="Upwind Differencing Scheme screenshot" width="820"></a><br>
  <sub>Upwind Differencing Scheme in use</sub>
</p>
<!-- HERO:END -->

## About

The one dimensional wave propagation equation is given by 

<img width="219" alt="image" src="https://user-images.githubusercontent.com/73946469/126501812-364fb701-13a0-4ab8-8dda-539beab539f8.png">

<img width="220" alt="image" src="https://user-images.githubusercontent.com/73946469/126501825-11d2c7d8-2b01-4ef6-9911-5c7e782409b2.png">

where the initial conditions are to be stated by
<img width="364" alt="image" src="https://user-images.githubusercontent.com/73946469/126501764-b9d3242a-3e84-448f-8e05-e37ef561b794.png">
<img width="416" alt="image" src="https://user-images.githubusercontent.com/73946469/126501779-23f87ac2-0ac1-4707-821e-b18cd34eab37.png">

Dx is fixed to a value of 0.01, while u’s and dt’s values are given by 0.09 and 0.01

The solution by the first order backward differencing scheme accurate in first order in time and space is to be given by the equation below.

<img width="219" alt="image" src="https://user-images.githubusercontent.com/73946469/126502488-2993e020-7d56-417b-a5e1-f12470168e09.png">
where the scheme is stable for C ≤1, having an order of accuracy of [∆𝑡,∆𝑥].

## License

Released under the [MIT License](LICENSE) © 2026 Juwen Lie. Contributions are welcome under the same license; see the [contributing guide](https://github.com/juw12/.github/blob/main/CONTRIBUTING.md) and [Code of Conduct](https://github.com/juw12/.github/blob/main/CODE_OF_CONDUCT.md).
