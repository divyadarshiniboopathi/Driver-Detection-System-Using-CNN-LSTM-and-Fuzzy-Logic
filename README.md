# Driver-Detection-System-Using-CNN-LSTM-and-Fuzzy-Logic
A Hybrid CNN-LSTM and Fuzzy Logic  Model for Real Time Cognitive Distraction in  Drivers.

Here, we present a hybrid distraction detection system based on eye aspect ratio (EAR) and head tilt angle, derived from facial landmarks using Mediapipe. The process involves labelling 15-frame segments using a fuzzy inference system (FIS) based on these feature points and classifying distraction levels into mild, medium, or severe. These fuzzy-labelled time series are subsequently employed to train a Long Short-Term Memory (LSTM) model to learn temporal patterns in driver behaviour. The system can successfully detect distraction severity by inspecting change in eye and head movement over time.
