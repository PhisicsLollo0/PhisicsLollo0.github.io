--------------------------------------------------------------------------------
Byte-by-byte Description of file: cavallo23.csv
--------------------------------------------------------------------------------
 Bytes Format Units  Label     Explanations
--------------------------------------------------------------------------------
  1- 20   A20    ---    Cluster    Cluster name
 22- 22   A1     ---    kind      ? [omg] Type of object (o: open cluster, m:
                                moving group, g: globular cluster) from HR23
 24- 43   F20.16 deg    RA        [0.4/359.62] Mean right ascension of cluster’s
                                members
 45- 64   F20.16 deg    DEC       [-82.22/87.09] Mean declination of cluster’s
                                memebers
 66- 72   F7.3   mas    plx       [-0.04/40.19] Mean parallax of cluster’s
                                members
 74- 78   F5.3   mas    e_plx     [0.01/0.15] Error on the parallax
 80- 84   F5.2   ---    CMDclass  ? [0/1] 50th percentile of CMD class from HR23
 86- 86   I1     ---    quality    [0/3] Quality of the predictions (0: gold
                                sample 1: silver sample 2:bronze sample 3:wood
                                sample)
 88- 91   F4.2   dex    logAge_16 [5.44/9.98] 16th percentile of logAge
                                predictions of the ANNs
 93- 97   F5.2   dex    logAge_50 [5.74/10.35] 50th percentile of logAge
                                predictions of the ANNs
 99-103   F5.2   dex    logAge_84 [5.97/10.78] 84th percentile of logAge
                                predictions of the ANNs
105-109   F5.2   dex    FeH_16    [-3.16/1.15] 16th percentile of [Fe/H]
                                predictions of the ANNs
111-115   F5.2   dex    FeH_50    [-2.61/1.32] 50th percentile of [Fe/H]
                                predictions of the ANNs
117-121   F5.2   dex    FeH_84    [-2.19/1.54] 84th percentile of [Fe/H]
                                predictions of the ANNs
123-126   F4.2   mag    Av_16      16th percentile of V-band extinction
                                predictions of the ANNs
128-131   F4.2   mag    Av_50      50th percentile of V-band extinction
                                predictions of the ANNs
133-136   F4.2   mag    Av_84      84th percentile of V-band extinction
                                predictions of the ANNs
138-142   F5.2   mag    dMod_16   [1.41/15.68] 16th percentile of distance
                                module predictions of the ANNs
144-148   F5.2   mag    dMod_50   [1.88/16.03] 50th percentile of distance
                                module predictions of the ANNs
150-154   F5.2   mag    dMod_84   [2.25/16.57] 84th percentile of distance
                                module predictions of the ANNs
156-175   F20.16 kpc    X         [-15.24/13.89] X coordinate in galactocentric
                                galactic coordinates (as predicted by the ANNs)
177-199   E23.16 kpc    Y         [-11.64/14.93] Y coordinate in galactocentric
                                galactic coordinates (as predicted by the ANNs)
201-223   E23.16 kpc    Z         [-6.61/9.19] Z coordinate in galactocentric
                                galactic coordinates (as predicted by the ANNs)
225-230   F6.3   kpc    Rgc       [0.27/23.5] Distance from Galactic centre (as
                                predicted by the ANNs and assuming Sun Rgc =
                                8.122 kpc)

--------------------------------------------------------------------------------


Acknowledgements: Lorenzo Cavallo lorenzo.cavallo(at)phd.unipd

References:  https://ui.adsabs.harvard.edu/abs/2023A%26A...673A.114H/abstract : H23

================================================================================

