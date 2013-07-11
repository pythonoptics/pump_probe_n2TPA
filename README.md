pump_probe_n2TPA
================

The main program is sim_vs_exp

Returns
  the output of the lock-in amplifier in a pump-probe experiment, the experiment is similar to [1]

Tips:

  To make sure that the results of the simulation are reasonable one should
  first test the pulse propagation using main_pump_probe.py for: delta_tau = [min_delta, 0, max_delta]
  If the pulses after the simulation lie inside the window span and nothing strange is observed its a reasonable assumption to expect that it will work fine for the other delta_tau.
  If not a bigger window span, t_point or z_points should be tested first.
  The firts paper that used the simulator is [2].
  The example is shown in work [3] and can also be cited
  
  References:
  
  [1] Vallaitis, T., Koos, C., Bonk, R., Freude, W., Laemmlin, M., Meuer, C., Bimberg, D., et al. (2008). Slow and fast dynamics of gain and phase in a quantum dot semiconductor optical amplifier. Optics express, 16(1), 170–178. Retrieved from http://www.ncbi.nlm.nih.gov/pubmed/18521145
  
  [2] Matres, J., Lacava, C., Ballesteros, G. C., Minzioni, P., Cristiani, I., Marti, J., Fédéli, J. M., et al. (2012). Low TPA and free-carrier effects in silicon nanocrystal-based horizontal slot waveguides. Opt. Express, 20(21), 23838–23845. doi:10.1364/OE.20.023838
  
  [3] Matres, J., Ballesteros, G. C., Gautier, P., Marti, J., &amp; Oton, C. J. (2013). High nonlinear figure-of-merit amorphous silicon waveguides. Opt. Express, 21(4), 1164–1170.
