# PyPI grscheller-courses-pet-images

PyTorch based machine learning.

## PyTorch Machine Learning (ML)

* identify pets with ML
* not sure if `pet_images/` is the training set or not
 
## Factoids

* developed using both Python 3.12.4 and 3.10.13 (used by Udacity)
  * Udacity just upgraded the Python they use from 3.6.3 in June 2024
  * 3.6.3 was version of Python out when PyTorch was released in 2016
  * annotations would not have been usable for Python 3.6.3
* using `__future__` statement to import annotations
  * for use by Python std library typing module 
  * annotations targeted for Python 3.13.X

## Testing

The testing suite will be in the GitHub clone, it will not be installed
with the package. Not sure what I will be doing for this.

To kick off all tests,

```
   $ pytest tests/`
```

So that the test data is found, run the tests from the root of the clone
of the GitHub repo.

## Documentation

See: [documentation](https://grscheller.github.io/courses-pet-images)

## Source Code (GitHub)

See: [source code](https://github.com/grscheller/courses-pet-images)

## License Summary

Apache v2.0 License

See [LICENSE](LICENSE) for license details
and [NOTICE](NOTICE) for copyright details.
