# Shotokan
This repository serves as an initial collaborative knowledge base for the Shotokan style for [bassai-dai.com](http://www.bassai-dai.com).

## Guidelines for contributing:
* The format of the `.kata` and `.style` files(see below) may seem a bit odd. This is to ensure that the web-service can read the files easily consistently with the other bassai-dai.com repositories. Please do not alter this format.
* Do not plagiarise.
* Be as objective as possible. For example: Don't mention belt colours or exact grade levels when a kata is taught. Mentioning an interpretation of the bunkai is also frowned upon.

**Any violations of the above rules will lead to a rejected pull request.**

## Format:
### `.kata` files:
    name = {
     [
      "list of names",
      "of the kata",
      "goes here",
      "these names can",
      "also be in 日本語",
     ]
    }

    info = {
      """
        This should be the main body of text for the kata.
        The text within the triple double-quotes can span
        multiple lines without problem.
      """
    }

    links = {
      [
        "Another list similar to the names above",
        "but this time dedicated to links for",
        "webpages relevant to the kata"
      ]
    }

### `.style` files:
    name = {
     [
      "list of names of the style",
      "bonus points for name in 日本語",
     ]
    }

    origin = {
      """"
      Details of the origin of the style goes here,
      including the founder.
      """
    }

    info = {
      """
      Other non origin-related information goes here.
      """
    }
