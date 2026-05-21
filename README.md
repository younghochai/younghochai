# [Guideline for Contribution]
- Thank you for contributing to the project of the VE lab at [Chung-Ang University, GSAIM (The Graduate School of Advanced Imaging Science, Multimedia & Film)](https://gsaim.cau.ac.kr/)

# Contribution Guide
### You can contribute in various ways.

- Please feel free to post your opinions on the issue at any time! Sharing opinions is also a contribution.
- You can check the status of our papers on the [VE lab page.](https://blog.naver.com/velab)

## 1. Visit our Main Repositories
### [motion-matrix](https://github.com/younghochai/motion-matrix)
- [Motion-sphere](https://www.mdpi.com/2076-3417/10/18/6462), which is a novel trajectory-based visualization technique to represent human motion on a sphere.
- For detailed installation and usage manual, please refer to [OpenIA_3.0.pdf.](https://github.com/younghochai/motion-matrix/blob/OpenIA-master/OpenIA_3.0.pdf)

### [GNN-RL-Kinetic-Facade](https://github.com/younghochai/GNN-RL-Kinetic-Facade)
- [GNN-RL framework]([https://watermark02.silverchair.com/qwag038.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAA3UwggNxBgkqhkiG9w0BBwagggNiMIIDXgIBADCCA1cGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMwasvaoAcHjJPnJsNAgEQgIIDKL0IR_tMoJbc--tQ-JhWLuNYkzm0LM9vfY5F7BRLVjs1wu--RG-Wp2m_0IjCgwQocZI5-pB10ZgAPqNvrF3po5x05_dSrAUSagJ-fYhFOwxOIKxfps3pNqqVOC45SmaA7_FWH5ARy2WICpZwzf3kzrslE1ZJdtLl1Kvx7LZ4v1VImO2PSS2PpS3wI-gNErMunv5V_6VowKyg5gCgRZQnP29rggfhm8Xzg7XjTolVh_kvfiACIJoBcMQ2k8RUnnd3svTwCQuYxUq0NhG5NDOkj92vWth7liKXMC2yiYLx43XvtH_zX5ctDRzk47Goy5yq_CoUqUrQxTGVS9C5YM5dE0vOcakUm_tE9hO_kKIKdc8bs75pnJoEalRlqat59DvvGaSOQsMQ2u-Msetp7jt8PfKIxVLO3lFg_UkMOe1ojfFms3mRfqIPbhl1lM6ZR1m2MJEhdnOxOX77GMw1om1GNfSEiKc8Otek9N_nKylqHN8FE9Zjb2RXKcSEzyST5S30DT6L14gbbJySHLPsb8uz9TlyQC7pvdT2HsmZnNHcQPTAAOzTSO4Rr_OF0hjaXCOAF-_54hI_MmghtfbPElwIzpjpAbghhTvapzYf3QG0bJpBhNTHrKcuA73ySCUxUeLuXv6gsDBiFgg7WEcHKAidk2HWKAMOvy6ATWteCWRjo_wzl5db4MPK1gw8wr9_zcrroD93h4TDIyTMGzorh5w-3yxGt8RXOj7kFLAHgEHKU35RAZGP69uOV52x6L6GeM5YlGKbpKyx90G2JGnz3KXrqaujNZv1QT3eXTJh33C8J-Ntp7v9m9HLtMLlp9ZDuBra7UrggmyyH6-ch1p1j-xqvOkneYQ7H6tP3-ZxcSWUur4et0jZxckadNWzT4yHvEFEkXhXNTpbOF3JZYQTMcTSXZMblzBHy2oziRxeepICfTppgF0zU15fgjQYC4nzaPYwpHUtd5Gd5-o9j6VixM3P0W69LKFv6z3IDXZNjsGciSnz4ojy6amsoGDlH98ksULFPfLXhtZVfEq-Y5YjWaYVNjBM1dU2mcSIz0z5HpHado_kKUOroGCDsgg](https://academic.oup.com/jcde/article/13/5/1/8655903?guestAccessKey=)), which is a real-time collective control of a large-scale kinetic facade via a GNN surrogate model and PPO reinforcement learning.

### [ChoreoTransformer](https://github.com/younghochai/ChoreoTransformer)
- [ChoreoTransformer](https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE12318091&width=1252), which is a motion editor from non-expert mocap data to expert motion.
- For detailed installation and usage manual, please refer to [ChoreoTransformer Guide.pdf.](https://github.com/younghochai/ChoreoTransformer/blob/main/ChoreoTransformer%20Guide.pdf)

### [BodyGestureGenerator](https://github.com/younghochai/BodyGestureGenerator)
- BodyGestureGenerator, which is a human body motion authoring tool for generating, visualizing, and editing gesture motions.

### [ConductingMotionAuthoring](https://github.com/younghochai/ConductingMotionAuthoring)
- ConductingMotionAuthoring, which is a Unity-based authoring system for creating and editing conducting motions, including beat patterns and expressive gestures.

### [AngleSpace](https://github.com/younghochai/AngleSpace)
- AngleSpace, which is a motion analysis tool for visualizing human motion joints.

### [Metaverse_VElab](https://github.com/younghochai/Metaverse_VElab)
- Metaverse_VElab, which is a Unity-based metaverse and motion capture platform for visualizing sensor-driven avatar motions in a multi-user virtual environment.

### [Utility](https://github.com/younghochai/Utility)
- It provides various functions for analyzing and editing motion data.

## 2. Pull-request Guidance
- If you are not contributor, please **fork** our repositories first, and then **pull-request** your contributions.
- The pull-request format is as follows.
  
### Description

Briefly describe what this Pull Request does.

(Example:
This PR adds a CSV-based conducting motion playback feature.)

### Changes

List the main changes included in this PR.

(Example:
- Added CSV file loader for conducting motion data
- Implemented beat pattern playback
- Added keyboard controls for cue and cut-off gestures)

### Test Checklist

Describe how you tested your changes.

(Example:
- [ ] Checked that CSV files are loaded correctly
- [ ] Verified that the avatar motion plays in Unity
- [ ] Confirmed that no errors appear in the console)


## 3. Issue
- If you have any questions or discussion, don't hesitate to share the **issue**.
- You can share various opinions in issues and contribute features that need to be added or modified to pull-requests.
