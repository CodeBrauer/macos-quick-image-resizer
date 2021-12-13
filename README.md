## Installation

1. Run `install.sh`
2. (Optional) Translate the notification to your language (DeepL is your friend)
3. Open the Workflow file with Automator, Choose "File" → "Convert In..." → "Service" → Save.

## Usage

1. In Finder right click any image file(s)
2. Go to services
3. Choose your service name (in my case "Bilder verkleinern")
4. A/multiple {filename}-resized.jpg will pop up in the same directory

## Options
Currently there no options. You can adjust the default settings in the script in Automator.

- `-resize 2560x1440\>`will shrink everything that is larger to the maximum height/width - ratio will be kept
- `-quality 80` will compress the jpg to quality of 80% (0-100%)