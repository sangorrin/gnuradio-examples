# gnuradio-examples
Repository for example gnuradio files.

Ref: https://github.com/sangorrin/notes/blob/master/sdr.txt

- gnuradio-spectrum-fm-nhk.grc: simple configuration that just connects
  the source to a FFT visualizer so that you can see a peak at 82.5MHz
  which is the NHK channel in Tokyo.

- gnuradio-spectrum-and-listen-fm-nhk.grc: allows decoding and listening to
  the FM NHK channel in Tokyo. So it includes filters, an FM receiver, an
  audio sink and custom sliders for tuning.

- gnuradio-spectrum-and-listen-tokyofm.grc: like gnuradio-spectrum-fm-nhk.grc
  but we just changed the frequency to 80Mhz, the one used by TokyoFM which
  is located near the Hanzomon subway station.
  
- gnuradio-spectrum-and-listen-tokyofm-qt.grc: like 
  gnuradio-spectrum-and-listen-tokyofm.grc but using QT GUI widgets.

- gnuradio-spectrum-fm-nhk-qt.grc: like gnuradio-spectrum-fm-nhk.grc
  but using qt widgets.




