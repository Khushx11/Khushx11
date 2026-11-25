# Khush Bhavin Maru

I’m a Master of Artificial Intelligence and Machine Learning student at Adelaide University. My projects focus on evaluating ML models under realistic constraints and building software that makes the results easy to inspect and reproduce.

## Publications

**Sonic Aid** · *IOSR Journal of Engineering*, vol. 15, issue 6, series 1, pp. 1–5, June 2025. [Read the paper](https://iosrjen.org/Papers/vol15_issue6/A15060105.pdf)

Khush Maru (first author), Nevil Parekh, Hardik Patel, Vaishali Wadhe, and Moinuddin Sheikh.

The original study explored speech-versus-music classification for sensory accessibility using sub-band coding, SVMs and Gaussian mixture models. The paper reported 94% classification accuracy. The current [SonicAid demo](https://github.com/Khushx11/SonicAid) evaluates environmental sounds on ESC-10.

## Start with a demo

- **See a document correction:** Upload a scan, trace a field to its page, and approve an export. [Invoice review demo](https://github.com/Khushx11/structured-invoice-extraction#try-the-fictional-demo)
- **Listen to a live model:** Follow environmental-sound predictions as five-second audio windows arrive. [SonicAid demo](https://github.com/Khushx11/SonicAid#quick-demo)
- **Inspect an evaluation:** Compare image and text models under missing and shuffled inputs. [Disaster classifier demo](https://github.com/Khushx11/disaster-image-classifier#quick-demo)

## Selected projects

- **Traffic Signal Queue Estimator.** Built a fixed-camera lane queue prototype with vehicle tracking and explicit uncertainty. The FHWA pilot exposed detector coverage gaps; real-world count accuracy remains unverified. [Project and pilot](https://github.com/Khushx11/traffic-signal-queue-estimator)
- **Structured Invoice Extraction and Review.** Built a local invoice OCR and review workflow with source highlights, an audit trail and structured export. Measured full-record automation on fictional invoices and amount extraction on real FCC documents. [Project and demo](https://github.com/Khushx11/structured-invoice-extraction)
- **Multimodal disaster image classification.** Compared text, image and fusion models on CrisisMMD. Late fusion achieved mean clean-test macro-F1 of 0.8168. The prespecified gated-fusion comparison was inconclusive. [Project and dashboard](https://github.com/Khushx11/disaster-image-classifier) · [Evidence checks](https://github.com/Khushx11/disaster-image-classifier/actions/runs/45450963072) · [Captioned demo](https://raw.githubusercontent.com/Khushx11/disaster-image-classifier/main/docs/demo/walkthrough.mp4)
- **Retail discount response.** Compared forecasts of next-week observed unit sales. LightGBM Tweedie had the lowest mean WAPE at 67.48% in the historical evaluation. Discount sweeps show model sensitivity. [Project and dashboard](https://github.com/Khushx11/retail-discount-response) · [Feature rebuild](https://github.com/Khushx11/retail-discount-response/actions/runs/45437888629)
- **SonicAid.** Built a WebSocket audio classifier using a checkpoint trained on ESC-10. Five-fold evaluation across 400 clips yielded 80.00% pooled accuracy and 0.8016 macro-F1. [Project and model card](https://github.com/Khushx11/SonicAid) · [Five-fold training](https://github.com/Khushx11/SonicAid/actions/runs/45433042812) · [Captioned demo](https://raw.githubusercontent.com/Khushx11/SonicAid/main/docs/demo/walkthrough.mp4)
- **DataInsightKit.** Built a local CSV profiler with a CLI, browser dashboard, input-handling tests and measured performance on documented workloads. [Project and benchmarks](https://github.com/Khushx11/datainsightkit-python) · [CLI benchmark](https://github.com/Khushx11/datainsightkit-python/actions/runs/45435457875)
- **MNIST reliability study.** Tested calibration and abstention under noise, rotation and occlusion on the official held-out split for digits 1 and 7. [Project and results](https://github.com/Khushx11/mnist-classification-and-clustering) · [Held-out evaluation](https://github.com/Khushx11/mnist-classification-and-clustering/actions/runs/45435452942)
- **Twitter sentiment analysis.** Evaluated a word and character TF-IDF classifier on 12,284 official TweetEval test posts. Logistic regression achieved 62.23% macro recall. [Project and dashboard](https://github.com/Khushx11/twitter-sentiment-analysis) · [Benchmark results](https://github.com/Khushx11/twitter-sentiment-analysis/blob/main/docs/tweeteval-results.json)
- **NumCompute.** Implemented sorting, search and ranking modules for the COMP 5004 group project. The portfolio edition includes the original coursework and a Palmer Penguins streaming ML extension. [Project and team credits](https://github.com/Khushx11/numcompute-penguins-streaming)
- **Handwritten inventory sheet digitiser.** Built a local stocktake review workflow with source-linked OCR, recorded approvals, and verified CSV/JSON exports. Benchmarked procedural sheets and composites from held-out writers separately. [Project and walkthrough](https://github.com/Khushx11/handwritten-inventory-digitiser)
