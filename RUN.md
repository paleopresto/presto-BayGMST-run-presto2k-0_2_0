# PReSto BayGMST run on Presto2k 0.2.0

- Data: presto-recipes pre-release [pools-2026-11-17b-0_2_0b](https://github.com/paleopresto/presto-recipes/releases/tag/pools-2026-11-17b-0_2_0b), pool [`Presto2k_0_2_0_localfdr10`](https://github.com/paleopresto/presto-recipes/blob/735d28a4cb22c555dd4a529488f7d4dd39391f25/pools/config/Presto2k_0_2_0_localfdr10.yml): 226 annual records of Presto2k 0.2.0 (LiPDverse export 2026-11-17b) that correlate with local HadCRUT5 temperature with the sign of their temperature interpretation, or the sign their proxy implies (BH FDR < 0.10, 1850-2000, lag-1 at most 0.98).
- Code and config: those of [presto-BayGMST-run-presto2k-0_1_0](https://github.com/paleopresto/presto-BayGMST-run-presto2k-0_1_0), including the PCR reduced proxy, unchanged.

The first run (f36645e) used 228 records; the revised screen drops the two coral d13C series of CO14OSPA, which had passed on negative correlations without a recorded temperature sign.

Committing `query_params.json` triggers the reconstruction workflow.
