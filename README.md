# spoken language identification

Analyze audio to identify a language.
The solution uses the CNN network in order to detect language specific phonems.
It supports 3 languages: English, German and Spanish.

## Demo

TODO dockerize

## Train

### Prerequisites

* ffmpeg is installed (tested with 3.4.2)
* sox is installed (tested with 14.4.2)

### Steps

1. Fetch the dataset
1. Generate samples
1. Generate features
1. Normalize features and build folds
1. Train the model