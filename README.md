In this visual grounding task, an image and a language query are encoded by an image encoder and a text
encoder, respectively. Then a learnable token is concatenated with the vision and language tokens to obtain
input tokens. The input tokens are passed through a vision-language fusion transformer. Finally, we use the
learnable token from the last layer to do bounding box regression for grounding an object corresponding to
the language query. The model is optimized by the GIoU loss and L1 loss.
