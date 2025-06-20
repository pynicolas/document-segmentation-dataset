# Document Segmentation Dataset

This repository contains a small, manually annotated dataset for training and evaluating document segmentation models. 
It is intended as a companion to the [document-segmentation-model](https://github.com/pynicolas/document-segmentation-model) repository, 
and is published under a restrictive license to prevent commercial reuse.

## Overview

- **Contents**: Images of documents (photos) and corresponding binary masks
- **Format**: JPEG images + PNG masks (1 channel)
- **Use case**: Semantic segmentation of documents in photos, typically as a first step in scanning workflows
- **Annotations**: Created manually using [LabelMe](https://github.com/wkentaro/labelme)
- **License**: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)

## Structure

The dataset is available via the [Releases](https://github.com/pynicolas/document-segmentation-dataset/releases) section of this repository. It is structured as follows:

```
.
├── train/
│   ├── images/
│   │   ├── img001.jpg
│   │   └── ...
│   └── masks/
│       ├── img001.png
│       └── ...
└──  val/
    ├── images/
    └── masks/
```

## License

The dataset is released under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)** license.

You are free to:

- **Share** — copy and redistribute the material in any medium or format
- **Adapt** — remix, transform, and build upon the material

Under the following terms:

- **Attribution** — You must give appropriate credit.
- **NonCommercial** — You may not use the material for commercial purposes.
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license.

See the full [license text here](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode).

## Credits

This dataset was manually created and curated as part of a broader effort to build ethical, privacy-respecting document scanning tools.

---

Feel free to open an issue if you notice errors in the annotations or would like to contribute improvements.
