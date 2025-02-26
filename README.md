## About

Data of Figs.2c,e,g, Figs.3b-e, Fig4e in the main text and Extended Data Figs.2b,d, Figs.3a-d, Figs.5a-c, and Figs.6c-e in the Extended Data. 



| Data Files                                                   | Descriptions                                                 | Details                                                      |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| **Main text figures data**                                   |                                                              |                                                              |
| Fig2c-Upper.csv                                              | Data of 'Fig. 2c, Upper panel'                               | Col1: " r/c", the filling ratio of the photonic crystals;<br>Col2: "fa/c", the eigenfrequencies of the PC at the Brillouin zone center. |
| Fig2c-LowerLeft.csv;<br>Fig2c-LowerMiddle.csv;<br>Fig2c-LowerRight.csv | Data of 'Fig. 2c,  Lower-left panel';<br>Data of 'Fig. 2c,  Lower-middle panel';<br>Data of 'Fig. 2c,  Lower-right panel'. | Col1: "k", High-symmetry path in the reciprocal space, where $k=0,1,2,3,4$ represents $M$, $Y$, $\Gamma $,  $X$ , $M$ points, respectively. <br/>Col2: "fa/c", the eigenfrequencies |
| Fig2e-Left.csv                                               | Data of 'Fig. 2e, Left panel'.                               | Col1: "Frequency(GHz)", the frequencies; <br>Col2: "k_eff(2$\pi$/a)", the wavevectors of the effective medium |
| Fig2e-Right.csv                                              | Data of 'Fig. 2e, Left panel'.                               | Col1: "Frequency(GHz)", the frequencies; <br/>Col2:"ez_eff", the effective relative permittivity $\varepsilon_z^\rm{eff}$; <br>Col3: "mud_eff", digonal term of the effective relative permeablity  $\mu_d^\rm{eff}$; <br/>Col4: "alpha_eff", off-diagonal term of the effective relative permeability $\alpha^\rm{eff}$. |
| Fig2g-Left.csv                                               | Data of 'Fig.2g, Left panel'                                 | Col1:“ky(2$\pi$/a)”, the wavevectors;<br>Col2:"Frequency(GHz)", the frequencies;<br>Col3:"LDOS(S/m)", the local density of states along $x=0$ of a supercell with $N_x=10$. |
| Fig2g-Experiment-data.csv                                    | The experimentally measured electric field data for metamaterial with a lattice constant of $a=17.2$ mm, which were used to generate 'Fig2g-Right.csv' | Col1:"Frequency(GHz)", the scanning requencies;<br>Col2:"y(m)", the probing postions;<br>Col3-4: The real and imaginary part of the mearused electric field. |
| Fig2g-Right.csv<br>                                          | Data of 'Fig. 2g, Right panel';<br>                          | Col1:“ky(2$\pi$/a)”, the wavevectors;<br>Col2:"Frequency(GHz)", the scanning frequencies;<br>Col3:"\|Ez\|", the magnitude of the electric field after Foureir transformation. |
|                                                              |                                                              |                                                              |
| Fig3b-Left.csv<br>Fig3b-Right.csv                            | Data of 'Fig.3b, Left panel';<br/>Data of 'Fig.3b, Right panel'. | Col1:“d(a)”, the slab thickness;<br/>Col2:"Frequency(GHz)", the scanning frequencies;<br/>Col3:"Abs[R]", the magnitude of the reflection coefficients;<br/>Col4: "Arg[R] (rad)", the phase of the reflection coefficients. |
| Fig3c.csv<br>Fig3d.csv <br>Fig3e.csv                         | Data of 'Fig.3c';<br>Data of 'Fig.3d';<br>Data of 'Fig.3e'.  | Col1:“ky(2$\pi$/a)”, the parallel component of wavevectors;<br>Col2:"Frequency(GHz)", the scanning frequencies;<br>Col3:"Abs[R]", the magnitude of the reflection coefficients;<br>Col4: "Arg[R]", the phase of the reflection coefficients. |
|                                                              |                                                              |                                                              |
| Folder-'Fig4e-ExperimentData-GenerateSTVP'                   | Experimental data of measuring STVP                          | The measurement system operates at a sampling rate of 80 GSa/s with an interpolation factor of 16.<br>The four subfolders include data of samples with 1-4 layers. <br>The name of '.csv' files denote the probe positions.<br>In each '.csv' file,  the 1st column is the time (s), and the 2nd column is the real part of the probed electric field. |
| Fig4e-STVP(1layer).csv <br>Fig4e-STVP(2layer).csv<br>Fig4e-STVP(3layer).csv<br>Fig4e-STVP(4layer).csv | Data of 'Fig.4e' for PC with 1-4 layers.<br>Data 'Fig4e-STVP(3layer).csv' was also used to Plot ''Extended Data Figs. 6c-e' | Col1:"t(ns)", the probe time whose origin was set at the center of the incident pulse.;<br>Col2:"y(m)",the probe postions along the scan line;<br>Col3:"Re[Ez]", the measured electric filed;<br>Col4:"Im[Ez]", the imaginary component of the analytical signal derived through Hilbert transformation of the measured electric field.<br> Col5:"Geometric Phases(Rad)", the geometric phases of the pulses extracted after eliminating the rapidly oscillating dynamical phases. |
|                                                              |                                                              |                                                              |
| **Extended data**                                            |                                                              |                                                              |
| Extended-Fig2b-Left.csv<br>Extended-Fig2d-Left.csv           | Data of 'Extended Data Fig. 2b, Left panel';<br/>Data of 'Extended Data Fig. 2d, Left panel'. | Col1:“ky(2$\pi$/a)”, the wavevectors;<br/>Col2:"Frequency(GHz)", the frequencies;<br/>Col3:"LDOS(S/m)", the local density of states along $x=0$ of a supercell with $N_x=10$. |
| Extended-Fig2b-Experiment-data.csv<br/>Extended-Fig2d-Experiment-data.csv | The experimentally measured electric field data for metamaterial with a lattice constant of $a=16$mm and $a=18.4$mm, which were used to generate data 'Extended-Fig2b-Right.csv' and 'Extended-Fig2d-Right.csv' | Col1:"Frequency(GHz)", the scanning requencies;<br/>Col2:"y(m)", the probing postions;<br/>Col3-4: The real and imaginary part of the mearused electric field. |
| Extended-Fig2b-Right.csv<br/>Extended-Fig2d-Right.csv        | Data of 'Extended Data Fig. 2b, Right panel';<br/>Data of 'Extended Data Fig. 2d, Right panel'. | Col1:“ky(2$\pi$/a)”, the wavevectors;<br>Col2:"Frequency(GHz)", the scanning frequencies;<br>Col3:"\|Ez\|", the magnitude of the electric field after Foureir transformation. |
|                                                              |                                                              |                                                              |
| Extended-Fig3a-FieldDistribution.csv                         | Data of exprimentally measured electric field distribution (10GHz, 4 layers), which were used to generate the field in 'Extended Data Fig. 3a' | Col1: "x(m)", x-coordinate of the probed fields <br/>Col2: "y(m)", y-coordinate of the probed fields <br/>Col3: "Re[Ez]", real part of the measured electric filed; <br/>Col4: "Im[Ez]", imaginary part of the measured electric filed. |
| Extended-Fig3b.csv                                           | Data of 'Extended Data Fig. 3b'                              | Col1: "Frequency(GHz)", scanning frequency;<br/>Col2: "kx($2\pi$/a)", kx axis of the Brillouin zone <br/>Col3: "ky($2\pi$/a)", ky axis of the Brillouin zone <br/>Col4: "Re[Ez]", real part of the Fourier component of electric filed; <br/>Col5: "Im[Ez]",  real part of the Fourier component of electric filed. |
| Extended-Fig3c.csv                                           | Data of 'Extended Data Fig. 3c'                              | Col1:"Layer", the layer of the PC slab;<br>Col2:“ky(2$\pi$/a)”, the parallel component of wavevectors;<br/>Col3:"Frequency(GHz)", the scanning frequencies;<br/>Col4:"Abs[R]", the magnitude of the reflection coefficients;<br/>Col5: "Arg[R]", the phase of the reflection coefficients. |
| Extended-Fig3-ExprimentData-1layer.csv<br>Extended-Fig3-ExprimentData-2layer.csv<br/>Extended-Fig3-ExprimentData-3layer.csv<br/>Extended-Fig3-ExprimentData-4layer.csv<br/> | Experimental data of the electirc field distribution before a metamaterial with 1-4 layers, which are used for calculating reflection coefficients. | Col1: "Frequency(GHz)", scanning frequency;<br>Col2: "x(m)", x-coordinate of the probed fields <br>Col3: "y(m)", y-coordinate of the probed fields <br>Col4: "Re[Ez]", real part of the measured electric filed; <br>Col5: "Im[Ez]", imaginary part of the measured electric filed. |
| Extended-Fig3d-1layer.csv<br>Extended-Fig3d-2layer.csv<br/>Extended-Fig3d-3layer.csv<br/>Extended-Fig3d-4layer.csv | Data of 'Extended Data Fig. 3d'                              | Col1:“ky(2$\pi$/a)”, the parallel component of wavevectors;<br/>Col2:"Frequency(GHz)", the scanning frequencies;<br/>Col3:"Abs[R]", the magnitude of the reflection coefficients;<br/>Col4: "Arg[R]", the phase of the reflection coefficients. |
|                                                              |                                                              |                                                              |
| Extended-Fig5a.csv                                           | Data of 'Extended Data Fig. 5a'                              | Col1:“ky(2$\pi$/a)”, the parallel component of wavevectors;<br/>Col2:"Frequency(GHz)", the scanning frequencies;<br/>Col3:"Abs[R]", the magnitude of the reflection coefficients;<br/>Col4: "Arg[R]", the phase of the reflection coefficients. |
| Extended-Fig5b.csv                                           | Data of 'Extended Data Fig. 5b'                              | Col1:“ky(2$\pi$/a)”, the wavevectors;<br/>Col2:"Frequency(GHz)", the frequencies;<br/>Col3:"LDOS(S/m)", the local density of states along $x=73 $ mm. |
| Extended-Fig5c.csv                                           | Data of 'Extended Data Fig. 5c'                              | Col1:“ky(2$\pi$/a)”, the wavevectors;<br>Col2:"Frequency(GHz)", the scanning frequencies;<br>Col3:"\|Ez\|", the magnitude of the electric field after Foureir transformation. |





<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formatted Table</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
            vertical-align: top;
        }
        th {
            background-color: #f2f2f2;
            text-align: left;
        }
        /* Adjust column widths */
        th:nth-child(1), td:nth-child(1) { width: 25%; }
        th:nth-child(2), td:nth-child(2) { width: 35%; }
        th:nth-child(3), td:nth-child(3) { width: 40%; }
    </style>
</head>
<body>



