<div class="typewriter-container">
  <div class="typewriter-text">
    Content not released yet. Stay Tuned!
  </div>
</div>

<style>
.typewriter-container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 150px;
  text-align: center;
}

.typewriter-text {
  font-size: 2rem;              /* Bigger text */
  font-weight: 800;             /* Extra Bold */
  color: #006be6;                  /* Dark Text (or use Tailwind text-primary) */
  overflow: hidden;
  border-right: 3px solid currentColor;
  white-space: nowrap;
  animation: typing 5.5s steps(40, end), blink 1.5s step-end infinite;
}

@keyframes typing {
  from { width: 0 }
  to { width: 100% }
}

@keyframes blink {
  50% { border-color: transparent }
}
</style>
