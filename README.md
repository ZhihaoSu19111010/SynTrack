<p align="center"> SynTrack: Multimodal Referring Multi-Object Tracking <br /> via Multi-Scale Cross-Modal Frequency Fusion and Temporal Contrastive Alignment

  
### Text–Speech–Vision Based MR-MOT Benchmarks
Multi-KITTI (Ours)

Our main benchmark is Multi-KITTI, a multimodal extension of KITTI where each video sequence is paired with synchronized text instructions + spoken commands describing the target object (e.g., “track the black car ahead and watch out for pedestrians”).
All annotations (IDs, bounding boxes, expressions, and commands) follow the standard MOT format.

Directory structure:

├── multi-kitti
│   ├── KITTI
│   │      ├── training
│   │      ├── labels_with_ids
│   ├── expressions
│   ├── speech
│   ├── seqmap_multikitti

Multi-KITTI+ (Ours, extended version)

We further release Multi-KITTI+, where each sequence contains richer multimodal descriptions, including long-form instructions and safety-aware cues.

Folder structure (same as Multi-KITTI with additional JSON metadata):

├── multi-kitti-plus
│   ├── KITTI
│   ├── labels_with_ids
│   ├── expressions_plus
│   ├── speech_plus
│   ├── seqmap_multikitti+

Multi-BDD (Ours)

We additionally construct a multimodal referring tracking benchmark from BDD100K, selecting 50 tracking sequences paired with text–speech expressions.

├── multi-bdd
│   ├── BDD
│   │     ├── training
│   │     ├── labels_with_ids
│   │     ├── expressions
│   │     ├── speech
│   ├── multi-bdd.train
│   ├── seqmap_bdd


Benchmark metadata files (seqmap+, multi-bdd.train, etc.) are available in the assets/ folder of the repository.

### Multimodal MR-MOT Benchmarks (Text + Speech + Vision)

We also release SynTrack-KITTI (Audio-Text-Vision), which includes synchronized visual frames, speech waveforms, and text instructions.
Download link: (your storage link)

### Update

2025.6.8 Released full MR-MOT benchmarks and SynTrack model code.

2024.12.10 Released Multi-KITTI+ and Multi-BDD annotations.

2024.11.20 Initial release of Multi-KITTI.
