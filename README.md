# Sonic-PI
use_bpm 160
use_synth :prophet


live_loop :strangers do
  play :c4
  sleep 0.5
  play :e4
  sleep 0.5
  play :g4
  sleep 0.5
  play :b4
  sleep 0.5
  play :c5
  sleep 0.5
  play :b4
  sleep 0.5
  play :g4
  sleep 0.5
  play :e4
  sleep 0.5
end

live_loop :heart do
  use_bpm 80
  sample :drum_bass_hard
  sleep 0.25
  sample :drum_bass_hard
  sleep 0.75
end

