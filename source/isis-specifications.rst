ISIS Specifications
===================

Updated: 2024-02

Notes:

* **Pool size**: The number of workspaces (VMs) available of a type to be claimed by the users.

* **Max size**: The maximum number of one type workspaces that can be used at the same time.

* If max number of workspaces are claimed, user would get alert "No workspaces available".

* If no workspaces in the pool are ready, user would get alert "No workspaces available".


.. list-table::
    :widths: 20 25 5 5 10 10 10 10 10
    :header-rows: 1

    * - Name
      - Flavor
      - GPUs
      - CPUs
      - RAM Gb
      - Pool Size
      - Max Size
      - Instrument(s)
      - Group(s)
    * - Crystallography
      - l2.medium
      - 0
      - 60
      - 245
      - 2
      - 5
      - | HRPD
        | INES
        | PEARL
        | POLARIS
        | SXD
        | WISH
      - | Crystallography
        | 
        |
        |
        |
        | Crystallography/Powder Defraction/Single Crystal
    * - Disordered Materials
      - l2.xsmall
      - 0
      - 16
      - 60
      - 7
      - 65
      - | GEM
        | NIMROD
        | SANDALS
      - Disordered Materials
    * - Disordered Materials - Developer
      - l2.small
      - 0
      - 30
      - 123
      - 2
      - 5
      - | GEM
        | NIMROD
        | SANDALS
      - | Crystallography/Disordered Materials
        | Disordered Materials
        |
    * - Engin-X
      - l2.tiny
      - 0
      - 8
      - 30
      - 3
      - 25
      - | ENGINX
        | IMAT
      - | Crystallography
        | Crystallography/Imaging/Diffraction
    * - Excitations Instrument Diagnostic
      - g-rtx4000.x1
      - 1
      - 12
      - 90
      - 1
      - 5
      - | ALF
        | LET
        | MAPS
        | MARI
        | MERLIN
      - Excitations
    * - Excitations Powder
      - l3.tiny
      - 0
      - 8
      - 30
      - 5
      - 50
      - | ALF
        | LET
        | MAPS
        | MARI
        | MERLIN
      - Excitations
    * - Excitations Single Crystal
      - l2.small
      - 0
      - 30
      - 123
      - 2
      - 60
      - | ALF
        | LET
        | MAPS
        | MARI
        | MERLIN
      - Excitations
    * - Excitations Single Crystal Large
      - l2.medium
      - 0
      - 60
      - 247
      - 1
      - 2
      - | ALF
        | LET
        | MAPS
        | MARI
        | MERLIN
      - Excitations
    * - McStas
      - l2.small
      - 0
      - 30
      - 123
      - 2
      - 10
      - NMIDG
      - NMIDG
    * - Molecular Spectroscopy
      - l2.small
      - 0
      - 30
      - 123
      - 7
      - 46
      - | IRIS
        | OSIRIS
        | TOSCA
        | VESUVIO
      - Molecular Spectroscopy
    * - Molecular Spectroscopy Advanced
      - l2.medium
      - 0
      - 60
      - 245
      - 2
      - 10
      - | IRIS
        | OSIRIS
        | TOSCA
        | VESUVIO
      - Molecular Spectroscopy
    * - Muon
      - l3.micro
      - 0
      - 4
      - 16
      - 5
      - 30
      - | ARGUS
        | CHRONUS
        | EMU
        | HIFI
        | MUSR
      - Muon
    * - Muon Simulation
      - l2.xsmall
      - 0
      - 16
      - 60
      - 3
      - 15
      - | ARGUS
        | CHRONUS
        | EMU
        | HIFI
        | MUSR
      - Muon
    * - Reflectometry
      - l2.xsmall
      - 0
      - 16
      - 60
      - 5
      - 55
      - | CRISP
        | INTER
        | OFFSPEC
        | POLREF
        | SURF
      - Reflectometry
    * - Reflectometry Advanced
      - l2.small
      - 0
      - 30
      - 123
      - 3
      - 50
      - | CRISP
        | INTER
        | OFFSPEC
        | POLREF
        | SURF
      - Reflectometry
    * - SANS
      - l2.xsmall
      - 0
      - 16
      - 60
      - 5
      - 50
      - | LARMOR
        | LOQ
        | ZOOM
      - Small Angle Scattering
    * - SANS for SANS2D
      - l2.small
      - 0
      - 30
      - 123
      - 5
      - 30
      - SANS2D
      - Small Angle Scattering
    * - SANS GPU
      - g-rtx4000.x1
      - 1
      - 12
      - 90
      - 1
      - 5
      - | LARMOR
        | LOQ
        | SANS2D
        | ZOOM
      - Small Angle Scattering
    * - Tomography Advanced
      - g-rtx4000.x2
      - 2
      - 28
      - 180
      - 2
      - 10
      - IMAT
      - Crystallography/Imaging/Diffraction
    * - Tomography Advanced Large
      - g-rtx4000.x4
      - 4
      - 60
      - 350
      - 3
      - 3
      - IMAT
      - Crystallography/Imaging/Diffraction
    * - Tomography Recommended
      - g-rtx4000.x1
      - 1
      - 12
      - 90
      - 3
      - 20
      - IMAT
      - Crystallography/Imaging/Diffraction
    * - Wish Diffuse Scattering Simulation
      - l2.small
      - 0
      - 30
      - 123
      - 3
      - 30
      - WISH
      - Crystallography/Powder Defraction/Single Crystal
    * - Wish Powder Diffraction
      - l3.tiny
      - 0
      - 8
      - 30
      - 5
      - 25
      - WISH
      - Crystallography/Powder Defraction/Single Crystal
    * - Wish Powder Diffraction Rocky 8 testing
      - l3.tiny
      - 0
      - 8
      - 30
      - 3
      - 25
      - WISH
      - Crystallography/Powder Defraction/Single Crystal
    * - Wish Single Crystal GPU Advanced
      - g-rtx4000.x2
      - 2
      - 28
      - 180
      - 2
      - 15
      - WISH
      - Crystallography/Powder Defraction/Single Crystal
    * - Wish Single Crystal GPU Rocky 8 testing
      - g-rtx4000.x2
      - 2
      - 28
      - 180
      - 1
      - 20
      - WISH
      - Crystallography/Powder Defraction/Single Crystal
    * - Wish Single Crystal GPU Standard
      - g-rtx4000.x1
      - 1
      - 12
      - 90
      - 2
      - 20
      - WISH
      - Crystallography/Powder Defraction/Single Crystal
