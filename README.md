body {
  background-color: #0d1117;
  color: #c9d1d9;
  font-family: Arial, sans-serif;
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 20px;
}

h1 {
  margin-bottom: 20px;
  font-size: 24px;
}

.grid {
  display: flex;
  gap: 4px;
}

.column {
  display: flex;
  flex-direction: column;
  gap: 4px;
}

.square {
  width: 15px;
  height: 15px;
  background-color: #161b22;
  border-radius: 2px;
  animation: pulse 1.5s infinite ease-in-out;
}

.square:nth-child(1) { animation-delay: 0s; }
.square:nth-child(2) { animation-delay: 0.1s; }
.square:nth-child(3) { animation-delay: 0.2s; }
.square:nth-child(4) { animation-delay: 0.3s; }
.square:nth-child(5) { animation-delay: 0.4s; }
.square:nth-child(6) { animation-delay: 0.5s; }
.square:nth-child(7) { animation-delay: 0.6s; }

@keyframes pulse {
  0%   { background-color: #0e4429; }
  50%  { background-color: #26a641; }
  100% { background-color: #0e4429; }
}