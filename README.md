(venv) thedyy@raspberrypi:~/Desktop/SmartFace $ pip install -r req_pi.txt
Collecting vosk==0.3.45 (from -r req_pi.txt (line 2))
  Using cached vosk-0.3.45-py3-none-linux_armv7l.whl.metadata (1.8 kB)
Collecting pyaudio==0.2.14 (from -r req_pi.txt (line 3))
  Using cached PyAudio-0.2.14.tar.gz (47 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting sentence-transformers==2.2.2 (from -r req_pi.txt (line 6))
  Using cached sentence-transformers-2.2.2.tar.gz (85 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting scikit-learn==1.3.0 (from -r req_pi.txt (line 9))
  Using cached scikit-learn-1.3.0.tar.gz (7.5 MB)
  Installing build dependencies ... error
  error: subprocess-exited-with-error
  
  × pip subprocess to install build dependencies did not run successfully.
  │ exit code: 1
  ╰─> [41 lines of output]
      Ignoring numpy: markers 'python_version == "3.10" and platform_system == "Windows" and platform_python_implementation != "PyPy"' don't match your environment
      Collecting setuptools
        Using cached setuptools-80.9.0-py3-none-any.whl.metadata (6.6 kB)
      Collecting wheel
        Using cached wheel-0.45.1-py3-none-any.whl.metadata (2.3 kB)
      Collecting Cython>=0.29.33
        Using cached cython-3.1.6-py3-none-any.whl.metadata (3.8 kB)
      Collecting oldest-supported-numpy
        Using cached oldest_supported_numpy-2023.12.21-py3-none-any.whl.metadata (9.8 kB)
      Collecting scipy>=1.5.0
        Using cached scipy-1.16.3.tar.gz (30.6 MB)
        Installing build dependencies: started
        Installing build dependencies: finished with status 'error'
        error: subprocess-exited-with-error
      
        × pip subprocess to install build dependencies did not run successfully.
        │ exit code: 1
        ╰─> [13 lines of output]
            Collecting meson-python<0.21.0,>=0.15.0
              Using cached meson_python-0.18.0-py3-none-any.whl.metadata (2.8 kB)
            Collecting Cython<3.2.0,>=3.0.8
              Using cached cython-3.1.6-py3-none-any.whl.metadata (3.8 kB)
            Collecting pybind11<3.1.0,>=2.13.2
              Using cached pybind11-3.0.1-py3-none-any.whl.metadata (10.0 kB)
            Collecting pythran<0.19.0,>=0.14.0
              Using cached pythran-0.18.0-py3-none-any.whl.metadata (7.9 kB)
            Collecting numpy<2.6,>=2.0.0
              Downloading numpy-2.3.4.tar.gz (20.6 MB)
            ERROR: Could not install packages due to an OSError: [Errno 28] No space left on device
      
                 ━━━━━━━━━━━━━━━━━━━╸                    10.5/20.6 MB 892.6 kB/s eta 0:00:12
            [end of output]
      
        note: This error originates from a subprocess, and is likely not a problem with pip.
      error: subprocess-exited-with-error
      
      × pip subprocess to install build dependencies did not run successfully.
      │ exit code: 1
      ╰─> See above for output.
      
      note: This error originates from a subprocess, and is likely not a problem with pip.
      [end of output]
  
  note: This error originates from a subprocess, and is likely not a problem with pip.
error: subprocess-exited-with-error

× pip subprocess to install build dependencies did not run successfully.
│ exit code: 1
╰─> See above for output.

note: This error originates from a subprocess, and is likely not a problem with pip.
(venv) thedyy@raspberrypi:~/Desktop/SmartFace $ 

