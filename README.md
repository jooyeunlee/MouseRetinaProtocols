# Functional and anatomical assessments of synapses in mouse retina

Source data supporting “Functional and anatomical assessments of synapses in mouse retina.” This repository includes electrophysiological traces for Figure 15B, light response measurements across cells, and a link to the raw confocal images for Figure 15C.

## Dataset contents

### [Figure15_traces.xlsx](Figure15_traces.xlsx) (Figure 15B)

The workbook contains three recordings from the same cell (D6b4Rc3), organized by worksheet.

| Worksheet | Epoch | Recording |
| --- | --- | --- |
| `spike` | 101 | Spike response |
| `excitation` | 102 | Excitatory current |
| `inhibition` | 203 | Inhibitory current |

Each worksheet contains time in milliseconds and the corresponding recorded signal in picoamperes (pA). The traces were exported from `D6b4Rc3_epochs_101_102_203.mat`.

Each recording epoch contains 16,000 samples acquired at 10 kHz (0.1 ms per sample) over 1.6 s. Time zero marks the start of the epoch. The 500 ms light stimulus begins at 500 ms and ends at 1,000 ms.

### [LightResponse.xlsx](LightResponse.xlsx)

This workbook contains responses to a 500 ms light step across cells. Each worksheet includes individual cell responses and the mean and standard error of the mean (SEM) across cells.

| Worksheet | Cells | Measurements |
| --- | ---: | --- |
| `Spikes per sec` | 22 | Peristimulus time histograms (PSTHs) in 20 ms bins and maximum firing rate during the light step (spikes/s) |
| `Excitation` | 11 | Excitatory current traces and peak current magnitudes (pA), and charge transfer (pC) |
| `Inhibition` | 17 | Inhibitory current traces and peak current magnitudes (pA), and charge transfer (pC) |

Current traces are tabulated at 1 ms intervals. Charge transfer was calculated over the 500 ms light-on period (500–1,000 ms). The inhibitory recordings were pooled across holding potentials ranging from +15 to +55 mV. Cell numbers are specific to each worksheet.

### Microscopy images (Figure 15C)

The raw confocal TIFF files are available on Zenodo. [Download image data](https://doi.org/10.5281/zenodo.23051601)

- **Lucifer Yellow** labels cell morphology.
- **PSD95** labels excitatory postsynaptic sites.
- **Gephyrin** labels inhibitory postsynaptic sites.

Images were acquired at a voxel size of 0.1020 × 0.1020 × 0.3002 µm (X × Y × Z). Panel C also includes a stretch view of a dendritic segment. Refer to the figure’s scale bars for the displayed spatial dimensions.
