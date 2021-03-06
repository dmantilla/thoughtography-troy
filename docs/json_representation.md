# JSON Representation

Partial representation of a document like [this](http://makezine.com/review/guide-to-3d-printing-2014/printrbot-plus/).

    {
      "_id" : 1,
      "title" : "PrintrBot Plus",
      "body" : [
        {
          "text" : "Overview",
          "children" : []
        },
        {
          "text" : "Upgradeable",
          "children" : [
            {
              "text" : "One of the Printrbot Plus’ attractive features is its upgradeability, great for people who aren’t sure if they want to spend money on options like multiple extruders or a higher-quality bed. Having the ability to update the printer also future-proofs it by allowing new hardware to be added as it gets developed."
            }
          ]
        },
        {
          "text" : "Support Your Objects, Level the Bed",
          "children" : [
            {
              "text" : "In testing, the printer seemed to struggle on very precise parts without any support, but by using support structures and by reducing overhangs, we were able to get our prints accurate to about 0.15mm."
            },
            {
              "text" : "Using PLA gave consistently better results than ABS, which had the unfortunate tendency to peel off the bed. We had our best results with the Printrbot Plus by leveling the bed, heating it to at least 80°C and the extruder to 240°C, and encouraging print adhesion by putting a thin layer of ABS goo on the bed. (ABS goo is easily made by mixing small bits of ABS with acetone.)"
            }
          ]
        },
        {
          "text" : "Untethered Printing Possible",
          "children" : [
            {
              "text" : "The Printrbot Plus is able to print untethered, although it’s not a completely straightforward process."
            },
            {
              "text" : "PRINTING UNTETHERED: THE MISSING CHAPTER",
              "children" : [
                {
                  "text" : "While the Repetier-Host software has built-in SD card support, it’s slow and buggy; don’t use it to transfer your G-code. Instead, unchain your computer with the following steps."
                },
                {
                  "text" : "- Use your laptop’s SD slot or a card reader to copy the G-code directly from the computer to the card."
                },
                {
                  "text" : "- Install the SD card into the printer, and connect the laptop."
                },
                {
                  "text" : "- Select the file to print in Repetier from the SD card manager, and initiate printing."
                },
                {
                  "text" : "Click Disconnect in Repetier and unplug the USB cable. The printer will continue to run."
                },
                {
                  "text" : "To resume control of your bot, simply plug the laptop in with USB and click Connect."
                }
              ]
            }
          ]
        }
      ]
    }