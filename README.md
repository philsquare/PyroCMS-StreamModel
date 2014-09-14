# PryoCMS PyroModel

## Overview

We created this model to make it much easier and quicker to interact with the PyroCMS Streams API.

### Requirements

* PyroCMS version 2.2.x

### Installation

* Download latest release
* Add the model to your module's model folder
* We extend this model with a separate base_model class (base_model.php). This way we can set our modules namespace or any other global settings/methods
* Make sure the base_model extends the parent constructor if you need to use $this->ci
* Then create your model files that will extend the base_model

### Support

Feel free to submit a pull request, create an issue or email us if you find a bug or would like to request a feature.