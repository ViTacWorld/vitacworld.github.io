# ViTacWorld Project Page

Updated September 28, 2026 to match the authors and experiments in the authors' latest arXiv manuscript.

## Current content

- Nine authors in manuscript order, with affiliations and corresponding-author marker.
- Updated 1080p overview video, with ShanghaiTech / InstAdapt title-card branding.
- Real-robot success rates: 50 trials per task, policy, and stage; 9 policy-stage rows.
- Policy evaluation: 3 tactile policies × 4 tasks, 50 matched initial states each (12 aggregate points / 600 real–imagined pairs). Pearson r = 0.863 and Spearman rho = 0.790.
- World-model quality: contact-transition clips and cross-view-attention ablation.

The site is plain HTML and CSS, with no build step or external JavaScript dependency. Preview with `python3 -m http.server` from this directory. Tables remain static HTML for accessibility and search indexing. The arXiv links resolve to the latest public version once the new manuscript is announced.

## Asset provenance

Research figures and videos are supplied by the ViTacWorld authors. The updated title uses the authors' existing ViTacWorld wordmark and institution marks from their earlier video. Anonymous author labels on the title and closing cards are replaced with the current author list. Experiment content is unchanged. The separate downloadable master supplied to the authors retains the original audio stream and copies the middle video stream; the website playback version uses high-quality 1080p H.264 encoding for efficient loading.

Layout inspiration: [Human-X](https://humanx-interaction.github.io/) and [Nerfies](https://nerfies.github.io/). No third-party research figures were reused.
