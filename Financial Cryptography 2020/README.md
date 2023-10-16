# Security Analysis on dBFT Protocol of NEO - Financial Cryptography 2020



Financial Cryptography 2020


NEO is one of the top public chains worldwide. It adopts a new consensus algorithm called delegated Byzantine Fault Tolerance (dBFT). In this article, we formalize dBFT via the state machine replication model and point out its potential issues. Our theoretical analysis indicates that dBFT could guarantee neither liveness nor safety, even if the number of Byzantine nodes is no more than the threshold, which has contradicted the established security claim. Then, we identify two attacks and successfully simulate them. Finally, we provide recommendations. Notably, NEO official team has accepted our suggested fixes.

