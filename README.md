body {
  margin: 0;
  padding: 0;
  background: linear-gradient(to bottom, #dfe9f3, #ffffff);
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  overflow: hidden;
}

.ball {
  width: 100px;
  height: 100px;
  background-color: #ff4757;
  border-radius: 50%;
  animation: bounce 1s infinite alternate ease-in-out;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
  cursor: pointer;
  transition: background-color 0.3s ease;
}

@keyframes bounce {
  from {
    transform: translateY(0);
  }
  to {
    transform: translateY(-200px);
  }
}