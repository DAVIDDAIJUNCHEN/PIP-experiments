Scripts for processing the text8 corpus

counting_all_data.py -- produces co-occurrence matrices of the text8 corpus
split_counting_all_data.py -- produces two co-occurrence matrices by splitting the text8 corpus into half and half. This is used to estimate the noise standard deviation.
PPMI.py -- produces the PPMI matrix (Word2Vec surrogate) from the co-occurrence matrices.
log_count.py -- produces the log_count matrix (GloVe surrogate) from the co-occurrence matrices.
noise_est.py -- produces the estimated noise standard deviation of the PPMI matrices built on two parts of the splitted dataset.
noise_est_logcount.py -- produces the estimated noise standard deviation of the log_count matrices built on two parts of the splitted dataset.

The .pkl files are obtained empirical spectrums of the PPMI and log count matrices