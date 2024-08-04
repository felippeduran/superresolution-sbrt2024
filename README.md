# Avaliação de funções-custo na super-resolução de imagens para jogos eletrônicos (SBrT 2024)
## Complementary Resource

This is a complementary resource for the article "Avaliação de funções-custo na super-resolução de imagens para jogos eletrônicos" published in the "Simpósio Brasileiro de Telecomunicações e Processamento de Sinais (SBrT) 2024". Here you can find the raw results from experiments and additional image samples.

## Instructions

The repository is organized with a [result_samples](result_samples) folder that contains extracted samples from the experiments. Their naming should describe the key parameters that generated the image and follow the format `<dataset>_<main_experiment>_<sample_id>_<run_parameters>.png`. Examples:
  * `viking_layers_2_x.png`: indicates the model input image of `sample_id` 2 for the perceptual layers experiment.
  * `viking_layers_block5_1.png`: indicates the model output image of `sample_id` 1 (ommited) for the perceptual layers experiment when using block5_1 as the perceptual loss output during training.
  * `viking_loss_mae.png`: indicates the model output image of `sample_id` 1 (ommited) for the weighted losses experiment when using a pure MAE loss.
  * `viking_loss_2_75gloss+25percep.png`: indicates the model output image of `sample_id` 2 for the weighted losses experiment when using 0.75 * G-loss + 0.25 perceptual loss.

## References

F. D. V. G dos Santos, R. Candido and M. T. M. Silva, “Avaliação de funções-custo na super-resolução de imagens para jogos eletrônicos,” *Simpósio Brasileiro de Telecomunicações e Processamento de Sinais*, 2024.

Unity Technologies, “Viking Village.” [Online]. Available: https://assetstore.unity.com/packages/essentials/tutorial-projects/viking-village-urp-29140
