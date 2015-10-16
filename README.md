# gestoos-cinder-samples 

A set of examples that show how to use Gestoos SDK interactive power with Cinder.

## Installation

1. Download Gestoos SDK from www.gestoos.com for your Windows or MacOS. Gestoos is free for research and non commercial purposes.
2. Clone this repository into your root gestoos path, for example:

        cd <your gestoos path>
        git clone https://github.com/gestoos/gestoos-cinder-samples.git 
3. (Windows only) Download Cinder library and copy the content of the <CINDER_DIR>/lib folder into <GESTOOS_DIR>/gestoos-cinder-samples/lib/win64/cinder_0.8.6_win/lib

## How to run the samples

Make sure you cloned this repository in the root folder of your Gestoos SDK copy.

For MacOS, open the XCode project included in the sample, then just click and play.
For Windows, open the Visual Studio 2013 project included in the sample, then just run.

## Creating your project

You can create new projects from scratch or just copying any existing project and changing name. We recommend to start from the EmptyExample sample.

Take a look at the Cinderactor class, which is a wrapper of the gestoos::nui::Interactor class. You may find most of you need there. The samples provided make use of Cinderactor, so you can check the code for details.

## Advanced interaction

For further information on Gestoos SDK API, please refer to www.gestoos.com or contact us at info@gestoos.com.
The SDK documentation also contains information about the classes being used in the cinder samples.
