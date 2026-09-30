# Functional and anatomical assessments of synapses in mouse retina
Source data supporting “Functional and anatomical assessments of synapses in mouse retina,” including electrophysiological recordings and links to raw confocal images hosted on Zenodo.


This repository contains electrophysiological traces and microscopy images supporting panels B and C of the Figure 15.

## Dataset contents

### Figure15_traces.xlsx — panel B

The Figure15_traces.xlsx workbook contains recordings from a cell, organized into three worksheets:

| Worksheet | Epoch | Recording |
|---|---|---|
| spike | 101 | Spike response |
| excitation | 102 | Excitatory current |
| inhibition | 203 | Inhibitory current |

Each worksheet contains a time column in milliseconds and the corresponding recorded signal.

**Recording timing**

- Sampling rate: 10 kHz
- Sampling interval: 0.1 ms
- Recording duration: 1.6 s
- Number of samples: 16,000 per trace
- Light stimulus onset: 500 ms
- Light stimulus offset: 1000 ms
- Stimulus duration: 500 ms

Time zero marks the beginning of each recording epoch.

The traces were exported from `D6b4Rc3_epochs_101_102_203.mat`. The spike, excitatory current, and inhibitory current traces were recorded from the same cell (D6b4Rc3) in separate recording epochs. The Excel export preserves the stored signal values without additional filtering, normalization, or baseline subtraction. 

The figure labels signal amplitudes in picoamp (pA).

### Microscopy images — panel C

The raw confocal TIFF files are available on Zenodo: [Download image data](https://doi.org/10.5281/zenodo.23051601).

- **Lucifer Yellow:** labeled cell morphology.
- **PSD95:** labeling associated with excitatory postsynaptic sites.
- **Gephyrin:** labeling associated with inhibitory postsynaptic sites.

Images were acquired with a voxel size of 0.1020 x 0.1020 x 0.3002 µm (X x Y x Z), corresponding to an XY pixel size of 0.1020 µm and a Z-step of 0.3002 µm. Panel C also includes an enlarged merged view of a dendritic segment. Refer to the figure’s scale bars for displayed spatial dimensions.

## Data scope

These files provide representative recordings and images.
