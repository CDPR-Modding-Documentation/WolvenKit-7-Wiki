# Console

The WolvenKit Conole is a handy tool that support the following command-line operations

*   **Bulk editing**

    Bulk edit all files in your mod project according with the following options.&#x20;

    > NOTE! WolvenKit also has a GUI for the bulk editor! You can find it under Tools > Experimental > Bulk Editor

\`\`\` -n Required. Specify the variable name. Example: -n autohidedistance

\-v Required. Specify the new variable value. Example: -v 9999

\-e Specify the file extension to edit. Example: -e w2mesh

\-c Specify the chunk name. Example: -c CMesh

\-t Specify the variable type. Available types are Bool, Uint64, Int64, Uint32, Int32, Uint16, Int16, Uint8, Int8 Example: -t Uint16

\-o Specify the option type. Default is replace. Available types are Multiplication (\*), Division (/), Addition (+), Subtraction (-), Example: -o + Example: -o /

\--exc Exclude the following values. Example: --exc=0,64,1028,2053

\--inc Include only the following values. Example: --inc=0,32,64

\--help Display this help screen.

\--version Display version information. \`\`\`
