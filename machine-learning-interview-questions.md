# Machine Learning (ML) System Design Interview Questions

> Deep dive into machine learning system design, including model selection, feature engineering, and production ML pipelines.

<!-- Keywords: ML design, machine learning interview, MLOps, model deployment, AI engineering -->

[⬅ Back to All Categories](README.md)

---

## [Large-Scale Recommendation Ranking with Long User Sequences](https://interviewgpt.deepchill.app/blogs/ml-design/large-scale-recommendation-ranking-with-long-user-sequences-miCSkBUc8JdrLfAxXV3DUB)
> 📅 *4/14/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a final-stage ranking system for a content discovery platform (like Pinterest) that effectively incorporates long-term user behavior history (1,000+ actions). Specifically, address the computational challenges of using attention mechanisms on long sequences within a low-latency production environment, discussing strategies for history retrieval, sequence compression, and online-offline architectural trade-offs.

</details>

---

## [Large-Scale Visual Discovery & Feed Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/large-scale-visual-discovery-feed-recommendation-system-fohWf6d83fwx471VayuR7o)
> 📅 *4/14/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale recommendation system for a visual discovery platform where users engage with items through saves and closeups. The system must handle a corpus of billions of items, prioritize graph-based relationships between items and collections, and maintain sub-150ms latency for a personalized home feed.

</details>

---

## [Uber Eats Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/uber-eats-recommendation-system-8gC9XPJiu3BtBCQZyMgyqg)
> 📅 *4/14/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale, real-time restaurant recommendation and ranking system for a food delivery platform. The system should optimize for conversion rate (CVR) while accounting for geographical constraints, real-time delivery estimates, and complex user preferences across millions of users and thousands of local merchants.

</details>

---

## [Scalable Personalized Content Discovery System](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-personalized-content-discovery-system-j8aWxXBehGxNdMjEeohky4)
> 📅 *4/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale, end-to-end recommendation engine for a news or article platform. The system must handle millions of items and users, optimize for diverse engagement metrics (CTR and Dwell Time), and ensure low-latency serving while addressing common challenges like content freshness, cold start, and position bias.

</details>

---

## [Large-Scale Real-time Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/large-scale-real-time-recommendation-system-6uxAREZ7qdCVTbUtHXASiw)
> 📅 *3/20/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale, real-time recommendation system for a content platform with 100M+ items. Detail the multi-stage funnel architecture, handle real-time feature engineering, address position bias, and ensure the system meets sub-200ms P99 latency constraints for 100k+ QPS.

</details>

---

## [Scalable Multi-Stage Ads Ranking System](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-multi-stage-ads-ranking-system-nwUJdqyDVS3aTyKbVzDn5U)
> 📅 *3/17/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale ads ranking and auction system capable of handling a corpus of 100 million ads and 500k QPS. The system must optimize for platform revenue (eCPM) while adhering to a strict 100ms latency budget. Detail the multi-stage funnel (retrieval, ranking, auction), feature engineering for sparse data, and strategies for model calibration and ad cold-start.

</details>

---

## [Large-Scale Ad Ranking System](https://interviewgpt.deepchill.app/blogs/ml-design/large-scale-ad-ranking-system-s4Pub6uU1f4hH6zN6dUMiS)
> 📅 *3/17/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design an end-to-end advertising ranking and auction system capable of handling 100k QPS and 10M+ candidates. The system must optimize for eCPM while maintaining sub-100ms latency, specifically addressing the challenges of feature sparsity, multi-stage filtering, and the feedback loop between impressions and conversions.

</details>

---

## [Unified ML Feature Platform Design](https://interviewgpt.deepchill.app/blogs/ml-design/unified-ml-feature-platform-design-32KBPEySaS4zP1jxDvGaiu)
> 📅 *3/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a scalable feature engineering platform that supports both batch and real-time streaming data processing, ensuring high-consistency for online model serving and offline model training at a multi-petabyte scale.

</details>

---

## [Large-Scale Short-Video Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/large-scale-short-video-recommendation-system-1ukTRV7PvvPSrTMgmAUSzs)
> 📅 *3/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design an end-to-end recommendation engine for a high-concurrency short-video platform, focusing on a multi-stage ranking funnel (retrieval and ranking) that optimizes for diverse engagement metrics and handles massive data scale with sub-200ms latency.

</details>

---

## [Large Language Model Chatbot System](https://interviewgpt.deepchill.app/blogs/ml-design/large-language-model-chatbot-system-31CHzkBvHTNDzty4YB3DDJ)
> 📅 *3/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a scalable, production-grade conversational AI system similar to ChatGPT. The system must support multi-turn dialogue, grounding via Retrieval-Augmented Generation (RAG) to minimize hallucinations, and a multi-stage alignment pipeline (SFT and DPO/RLHF). Constraints include a peak load of 5,000 QPS, a P99 Time to First Token (TTFT) of less than 200ms, and a robust safety moderation framework. Explain the end-to-end lifecycle from data curation and tokenization to high-throughput inference using modern memory management techniques like PagedAttention.

</details>

---

## [Scalable Real-Time Email Spam Filtering](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-real-time-email-spam-filtering-6jwQd6RDqk8LQw1ZFudn1s)
> 📅 *3/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a real-time, high-throughput spam detection system for a global email provider with over 1 billion users. The system must process 10 million QPS with a P99 latency under 20ms. Address the challenges of extreme class imbalance, the high cost of false positives (important emails marked as spam), and the adversarial nature of spam campaigns. Your design should include a multi-tiered architecture for computational efficiency, a mechanism for rapid adaptation to new threats via user feedback loops, and a strategy for ensuring privacy and robustness against adversarial attacks.

</details>

---

## [Short-Form Video Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/short-form-video-recommendation-system-wecMyZEX5wpxCMYeTfyWi1)
> 📅 *3/15/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale, real-time recommendation engine for a short-form video platform. The system must handle a corpus of over a billion items, provide sub-200ms latency for a 'For You' feed, and optimize for multiple engagement metrics including watch time and social interactions while effectively managing content cold-start and real-time user interest shifts.

</details>

---

## [Scalable ML Evaluation Framework](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-ml-evaluation-framework-rHF2xNZuEMxUM1Zw38E7i9)
> 📅 *3/13/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a comprehensive evaluation system for a high-scale recommendation engine. The system should address the gap between offline proxy metrics and online business objectives, handle selection bias in historical data, and provide a robust framework for A/B testing and long-term model performance monitoring.

</details>

---

## [High-Scale Payment Fraud Detection](https://interviewgpt.deepchill.app/blogs/ml-design/high-scale-payment-fraud-detection-ixsA8k7Jd3zF4EYt3Pax9F)
> 📅 *3/6/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design an end-to-end machine learning system for real-time payment fraud detection that processes 10k+ QPS with sub-100ms latency, specifically addressing the challenges of extreme class imbalance, feature freshness (velocity features), and delayed labels from chargebacks.

</details>

---

## [Scalable Toxic Content Moderation](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-toxic-content-moderation-dpXt79US7KuJo2nANMzmV1)
> 📅 *3/6/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-throughput, low-latency ML system for real-time toxic content detection and multi-label classification, capable of handling adversarial inputs and minimizing bias against protected groups at a scale of 100k+ QPS.

</details>

---

## [Autonomous Vehicle Perception System Design](https://interviewgpt.deepchill.app/blogs/ml-design/autonomous-vehicle-perception-system-design-iSjrokukVhxo9RnJnDRCYT)
> 📅 *3/6/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a scalable, real-time object detection and perception system for an autonomous vehicle fleet. Focus on the end-to-end data lifecycle, including on-device inference constraints, cloud-based data mining for rare edge cases, and a robust evaluation framework to ensure safety and reliability in diverse driving conditions.

</details>

---

## [Similar Listings Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/similar-listings-recommendation-system-rYSw3L6w5Bzr5XUxR4NumG)
> 📅 *2/28/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Imagine you are building a feature for a major vacation rental platform that suggests 'Similar Listings' to users based on the property they are currently viewing. Design an end-to-end machine learning system that identifies and ranks these recommendations to maximize booking conversions, while accounting for high-dimensional metadata, physical location constraints, and real-time availability.

</details>

---

## [Scalable Misinformation Detection System](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-misinformation-detection-system-6Sr9nDGHwdaCRtxYdv18rW)
> 📅 *2/28/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design an end-to-end machine learning system for a large-scale social media platform to detect and mitigate the spread of misinformation (fake news). The system should handle high-velocity content ingestion, utilize multimodal signals (text, images, and network propagation), and incorporate a human-in-the-loop feedback mechanism to maintain high precision and user trust.

</details>

---

## [ML-Driven Adaptive Rate Limiting](https://interviewgpt.deepchill.app/blogs/ml-design/ml-driven-adaptive-rate-limiting-9uYDfYHga2iYPBMHt3gcrc)
> 📅 *2/25/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

How would you design an intelligent, large-scale rate limiting system that uses machine learning to dynamically adjust request quotas based on user behavior and system health, ensuring high availability while mitigating sophisticated bot attacks?

</details>

---

## [Real-Time Bidding (RTB) System Design](https://interviewgpt.deepchill.app/blogs/ml-design/real-time-bidding-rtb-system-design-myqCy3pT8LHmw8eyE6xjLn)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale Demand Side Platform (DSP) capable of processing millions of bid requests per second from various ad exchanges. The system must predict the probability of user engagement (clicks/conversions) to calculate optimal bid prices in under 50 milliseconds, while managing advertiser budgets and optimizing for long-term Return on Ad Spend (ROAS).

</details>

---

## [Real-time Financial Forecasting System](https://interviewgpt.deepchill.app/blogs/ml-design/real-time-financial-forecasting-system-bwdFUtKmTSxzwpHqtwayn5)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a large-scale machine learning system to provide real-time, high-frequency price movement signals for a global trading platform. The system should handle millions of active users, ingest diverse data sources like market ticks and news sentiment, and maintain extreme low latency while addressing the unique challenges of financial time-series data such as non-stationarity and backtesting integrity.

</details>

---

## [Video Anomaly Detection System](https://interviewgpt.deepchill.app/blogs/ml-design/video-anomaly-detection-system-oKDZQsX2vZZqGodaB1564d)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a large-scale, automated video surveillance system capable of identifying and alerting on unusual or suspicious activities in real-time. The solution should handle thousands of concurrent camera streams, minimize false positives through human-in-the-loop feedback, and function efficiently across varying environments and lighting conditions.

</details>

---

## [Large-Scale Visual Search System](https://interviewgpt.deepchill.app/blogs/ml-design/large-scale-visual-search-system-6reWyA13bBHJxo5RQvJeYR)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design an end-to-end visual similarity and search system for a global e-commerce platform that allows users to find products using images. The system must scale to hundreds of millions of items, support sub-second latency, and optimize for business metrics like conversion rate and user engagement.

</details>

---

## [Large-Scale Visual Search System](https://interviewgpt.deepchill.app/blogs/ml-design/large-scale-visual-search-system-mwLbDacuP4ZhuEJ1k7LYR1)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design an end-to-end multi-modal image search engine capable of indexing billions of images and supporting both text-based and image-based queries with sub-second latency. The system should handle real-time content ingestion, ensure high relevance across diverse categories, and include robust mechanisms for ranking, filtering, and performance monitoring at scale.

</details>

---

## [Hierarchical Multi-label Document Classifier](https://interviewgpt.deepchill.app/blogs/ml-design/hierarchical-multi-label-document-classifier-h57U4TthbXFaXMb32WfFqt)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-throughput, low-latency machine learning system to automatically classify millions of multi-modal documents into a complex, hierarchical taxonomy with over 1,000 labels. The system must handle long-form text, provide calibrated confidence scores for automated downstream processing, and include a strategy for handling label drift and human-in-the-loop feedback.

</details>

---

## [Scalable Multi-Modal Content Moderation System](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-multi-modal-content-moderation-system-9g9VmeDZgWpmGpfMMwzidF)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale content moderation system for a global social media platform capable of processing billions of multi-modal posts per day. The system must automatically identify and action policy-violating content (e.g., hate speech, NSFW) in real-time while minimizing false positives and incorporating a human-in-the-loop workflow for high-uncertainty cases.

</details>

---

## [Adversarial Spam Detection at Scale](https://interviewgpt.deepchill.app/blogs/ml-design/adversarial-spam-detection-at-scale-bEps3c63vHcyrG3RP55dxj)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

How would you design a robust, real-time spam detection system for a global social media platform that handles billions of posts daily? The system must minimize the visibility of malicious content while maintaining extremely low false-positive rates, and it must be capable of adapting to rapidly changing adversarial tactics used by spammers.

</details>

---

## [Scalable LLM-based RAG Assistant](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-llm-based-rag-assistant-iKnVwv89QhDUoDqePBBpr3)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design an end-to-end enterprise chatbot system that leverages Large Language Models and Retrieval-Augmented Generation (RAG) to provide accurate, real-time responses based on a massive internal knowledge base. The system must handle high concurrency, ensure data privacy, and maintain high factual accuracy while minimizing latency for millions of users.

</details>

---

## [Social Graph Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/social-graph-recommendation-system-uvciYsZYktziDeGKVqSPFd)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a large-scale recommendation system for a social network that suggests potential connections to users. The system should leverage social graph structures, handle billions of edges, and optimize for long-term user engagement and connection quality while maintaining low latency and addressing challenges like cold-start users and position bias.

</details>

---

## [Ride-Sharing Dynamic Pricing System](https://interviewgpt.deepchill.app/blogs/ml-design/ride-sharing-dynamic-pricing-system-oM34RHXV1CJDLxXxTQ9shn)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a real-time dynamic pricing and surge engine for a global ride-hailing marketplace. The system should intelligently balance rider demand and driver supply across different geographic locations and time intervals to maximize marketplace efficiency and reliability, while handling high-scale streaming data and strict latency constraints.

</details>

---

## [Large-Scale Music Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/large-scale-music-recommendation-system-nJkUgfQB8uVUv5RLEUGL5D)
> 📅 *2/24/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale personalized music recommendation engine capable of serving hundreds of millions of users. The system should handle discovery (Discover Weekly style), real-time session updates, and effectively manage the balance between recommending popular content and discovering niche artists while maintaining strict sub-second latency requirements.

</details>

---

## [E-commerce Personalization Engine](https://interviewgpt.deepchill.app/blogs/ml-design/e-commerce-personalization-engine-u6uxZYYcRhheHFZku9p9DB)
> 📅 *2/21/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a large-scale product recommendation system for a global e-commerce platform that optimizes for multiple business objectives like click-through rate and purchase conversion. The system must handle a massive, dynamic catalog of millions of items, support real-time user session updates, and maintain strict low-latency requirements for a global user base.

</details>

---

## [Real-time Fraud Detection System](https://interviewgpt.deepchill.app/blogs/ml-design/real-time-fraud-detection-system-1476azX6zdq1AGM6PknKGj)
> 📅 *2/20/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-throughput, low-latency machine learning system to detect and prevent fraudulent transactions in real-time. The system must handle extreme class imbalance, evolving adversarial patterns, and delayed feedback from financial institutions while minimizing impact on legitimate user experience.

</details>

---

## [Ad Click-Through Rate Prediction System](https://interviewgpt.deepchill.app/blogs/ml-design/ad-click-through-rate-prediction-system-soXCdqpFhcmoXyaJHbBHvV)
> 📅 *2/18/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-scale advertising ranking system that predicts the probability of a user clicking on a specific ad creative. The system must handle high-cardinality data, ensure low-latency inference for real-time auctions, and maintain model freshness through a robust data and feature pipeline.

</details>

---

## [Scalable Video Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-video-recommendation-system-qPSdTdTazLJuEJJuUPXdvp)
> 📅 *2/17/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Design a high-throughput, low-latency recommendation engine for a global video sharing platform. The system should handle hundreds of millions of users and items, provide real-time personalization based on user behavior, and optimize for long-term engagement metrics like retention and watch time, while ensuring diversity and handling new content discovery.

</details>

---

## [Scalable Video Recommendation System](https://interviewgpt.deepchill.app/blogs/ml-design/scalable-video-recommendation-system-jsehg82pQ5kvmFPkM86dBE)
> 📅 *2/17/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

As a lead engineer at a global streaming service, how would you architect a production-grade recommendation engine to serve personalized video feeds to hundreds of millions of users while balancing engagement metrics like clicks and long-term watch time? Detail the end-to-end lifecycle from data ingestion to real-time inference and bias mitigation.

</details>

---

*Generated by [InterviewGPT](https://interviewgpt.ai) on Thu Apr 16 2026*
