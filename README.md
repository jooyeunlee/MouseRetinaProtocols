# Functional and anatomical assessments of synapses in mouse retina

Source data supporting “Functional and anatomical assessments of synapses in mouse retina.” This repository includes the electrophysiological traces and light response measurements for Figure 15, along with a link to the raw confocal images.

## Dataset contents

### [LightResponse.xlsx](LightResponse.xlsx)

This workbook contains the single-cell traces shown in Figure 15B and the light response data for Figure 15C, E, and G. The 500 ms light stimulus begins at 500 ms and ends at 1,000 ms, measured from the start of each recording epoch.

#### Single-cell traces (Figure 15B)

The spike, excitatory current, and inhibitory current traces were recorded from the same cell (D6b4Rc3) in separate epochs and exported from `D6b4Rc3_epochs_101_102_203.mat`.

| Epoch | Recording |
| --- | --- |
| 101 | Spike response |
| 102 | Excitatory current |
| 203 | Inhibitory current |

Each trace contains 16,000 samples acquired at 10 kHz (0.1 ms per sample) over 1.6 s. Time is given in milliseconds and signal amplitude in picoamperes (pA).

#### Light responses across cells

| Figure 15 panel | Worksheet | Response data |
| --- | --- | --- |
| C | `Spikes per sec` | Peristimulus time histograms (PSTHs) in 20 ms bins, including the mean and SEM across cells |
| E | `Excitation` | Individual excitatory current traces and the mean and SEM across cells |
| G | `Inhibition` | Individual inhibitory current traces and the mean and SEM across cells |

The workbook also includes each cell’s maximum firing rate during the light step, peak current magnitude (pA), and charge transfer (pC), as applicable. Current traces are tabulated at 1 ms intervals. Charge transfer was calculated over the 500 ms light-on period. Inhibitory recordings were pooled across holding potentials from +15 to +55 mV.

### Microscopy images

The raw confocal TIFF files are available on Zenodo. [Download image data](https://doi.org/10.5281/zenodo.23051601)

- **Lucifer Yellow** labels cell morphology.
- **PSD95** labels excitatory postsynaptic sites.
- **Gephyrin** labels inhibitory postsynaptic sites.

Images were acquired at a voxel size of 0.1020 × 0.1020 × 0.3002 µm (X × Y × Z). The figure also includes a stretch view of a dendritic segment. Refer to the scale bars for the displayed spatial dimensions.
