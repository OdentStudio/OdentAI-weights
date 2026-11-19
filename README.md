# Odent — model weights

The AI model weights used by OdentStudio's Blender add-ons, distributed
separately from the add-ons, under their own licence.

**Licence: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
— non-commercial use only.** Each pack carries its full terms, data sources
and the papers to cite.

You normally do not need to download anything by hand: the add-on shows the
licence and fetches the pack itself. On a computer without internet, download
the zip here, bring it over and install it from the add-on. Do not unpack it.

## OdentAI Segment

The model weights for the **OdentAI Segment 1.x** add-on.

- Download: [`OdentAI-weights-1.zip`](https://github.com/OdentStudio/OdentAI-weights/releases/tag/weights-1)
  (about 490 MB) — the four model files and the licence.
- In the add-on: **Download the model**, or **Install from file**.
- Terms, data source and citations: [LICENSE.md](LICENSE.md).

## FastTeeth (ODent5)

The teeth segmentation models used by **ODent5** for AI align and Teeth Seg.

- Download: [`fastteeth-v1.zip`](https://github.com/OdentStudio/OdentAI-weights/releases/tag/fastteeth-v1)
  (about 10 MB) — the two models, their settings, `model.json` and the licence.
- Author: Dr. Illia Fomenko DMD · published by OdentStudio.
- Terms, data sources and citations: `LICENSE.md` inside the zip.

## Data sources

The weights were trained on the **ToothFairy2** and **ToothFairy3** datasets
of the University of Modena and Reggio Emilia
([ditto.ing.unimore.it](https://ditto.ing.unimore.it), CC BY-NC-SA 4.0) and on
**DentVoxel** (You Zhou, Yan Xu, Mihai-Adrian Tarce, University of Hong Kong,
[doi:10.6084/m9.figshare.31239889.v2](https://doi.org/10.6084/m9.figshare.31239889.v2),
CC BY 4.0). Whenever you use these weights or results obtained with them,
acknowledge ToothFairy3 and DentVoxel as data sources and cite the papers
listed in the pack's LICENSE.md.

The weights may not be used for commercial purposes.

The add-ons are tools for 3D modelling and planning support, not certified
medical devices.
