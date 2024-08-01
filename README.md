# MHI2-Navignore

This repository includes a navignore file for VW MHI2 units that attempts to resolve an issue with previous navignore files failing to prevent the instrument cluster from continuing to display internal navigation maps whilst CarPlay navigation was active. This navignore is experimental and has been tested with a NAR MHI2 unit (MU1418). Changes were also added to try to support Android Auto but Android Auto has not been tested.

In most cases, you should use the navignore bundled with your MHI2 toolbox of choice rather than this navignore. Using this navignore is done at your own risk and is offered without warranty or support. To use this navignore, look into replacing the bundled navignore file with your MHI2 toolbox of choice.

Generation of this navignore file was made possible using information and resources from Andrew Leech and the MIB2 High lsd.jxe patching project (https://gitlab.com/alelec/mib2-lsd-patching).
