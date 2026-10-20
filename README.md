<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/evkit-logo-dark.svg">
    <img src="assets/evkit-logo-light.svg" alt="EVKit logo" width="600">
  </picture>
</p>

# EVKit

**An Open-source Flexible Toolkit for Efficient Event Camera Data Compression and Loading**

Yilun Wu<sup>1,2</sup> and Guido C. H. E. de Croon<sup>1</sup>

<sup>1</sup> Micro Air Vehicle Laboratory, Delft University of Technology<br>
<sup>2</sup> Machine Learning Group, Centrum Wiskunde & Informatica (CWI)

> [!NOTE]
> **Code coming soon.** We are preparing EVKit for public release and will publish the
> code in this repository very soon. Watch or star the repository to be notified when it
> is available.

## About

EVKit is an open-source toolkit that removes the data-loading bottleneck of event-based
vision research. It covers both recorded and synthetic event data:

- **PODCAST** (Pixel-Ordered Delta-Coordinates with Aligned Sign and Timestamp), a new
  event format that stores events in pixel order instead of time order, giving
  substantially smaller files and much faster decoding than existing formats.
- **Fast data loading** that decompresses, filters and augments event streams and converts
  them into frame-like representations (voxel grids, time surfaces, ...) on the fly, on CPUs
  alone, so intermediate representations no longer need to be precomputed.
- **Synthetic events from high-frame-rate video**, stored compactly and converted to event
  representations at load time with a physically grounded RGB-to-event model.
- **Dataset conversion utilities** and pre-converted popular datasets hosted on Hugging Face.

## Citation

A paper describing EVKit is forthcoming; citation details will be added here.

## License

EVKit will be released under the MIT License.
