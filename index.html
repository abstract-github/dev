import React, { useState, useEffect, useCallback } from 'react';

const AbstractWebsite = () => {
  const [isMenuOpen, setIsMenuOpen] = useState(false);
  const [shapes, setShapes] = useState([]);
  const [mousePosition, setMousePosition] = useState({ x: 0, y: 0 });

  const generateShapes = useCallback(() => {
    const newShapes = [];
    const shapeTypes = ['square', 'circle', 'triangle', 'line'];
    for (let i = 0; i < 25; i++) {
      newShapes.push({
        type: shapeTypes[Math.floor(Math.random() * shapeTypes.length)],
        size: Math.random() * 100 + 20,
        x: Math.random() * window.innerWidth,
        y: Math.random() * window.innerHeight,
        xSpeed: (Math.random() - 0.5) * 1.5,
        ySpeed: (Math.random() - 0.5) * 1.5,
        rotation: Math.random() * 360,
        rotationSpeed: (Math.random() - 0.5) * 1.5,
        opacity: Math.random() * 0.5 + 0.1,
      });
    }
    setShapes(newShapes);
  }, []);

  useEffect(() => {
    generateShapes();
    const moveShapes = setInterval(() => {
      setShapes(prevShapes => prevShapes.map(shape => ({
        ...shape,
        x: (shape.x + shape.xSpeed + window.innerWidth) % window.innerWidth,
        y: (shape.y + shape.ySpeed + window.innerHeight) % window.innerHeight,
        rotation: (shape.rotation + shape.rotationSpeed) % 360,
      })));
    }, 30);

    const handleMouseMove = (event) => {
      setMousePosition({ x: event.clientX, y: event.clientY });
    };

    window.addEventListener('mousemove', handleMouseMove);

    return () => {
      clearInterval(moveShapes);
      window.removeEventListener('mousemove', handleMouseMove);
    };
  }, [generateShapes]);

  return (
    <div className="abstract-website">
      <div className="background">
        {shapes.map((shape, index) => (
          <div
            key={index}
            className={`shape ${shape.type}`}
            style={{
              width: `${shape.size}px`,
              height: shape.type === 'line' ? '2px' : `${shape.size}px`,
              left: `${shape.x}px`,
              top: `${shape.y}px`,
              transform: `rotate(${shape.rotation}deg)`,
              opacity: shape.opacity,
            }}
          />
        ))}
      </div>

      <header>
        <nav className={isMenuOpen ? 'open' : ''}>
          <button className="menu-toggle" onClick={() => setIsMenuOpen(!isMenuOpen)}>
            <div className="menu-icon"></div>
          </button>
          <div className="menu-items">
            <a href="#projects">Projects</a>
            <a href="#about">About</a>
            <a href="#blog">Blog</a>
            <a href="#contact">Contact</a>
            <a href="#hire" className="hire-me">Hire Me</a>
          </div>
        </nav>
      </header>

      <main>
        <h1 className="animated-name">
          <span className="char">a</span>
          <span className="char">b</span>
          <span className="char">s</span>
          <span className="char">t</span>
          <span className="char">r</span>
          <span className="char">a</span>
          <span className="char">c</span>
          <span className="char">t</span>
          <span className="char">.</span>
          <span className="char">d</span>
          <span className="char">e</span>
          <span className="char">v</span>
        </h1>
        <p>AI • Mathematics • Informatics • Algorithms</p>
        <a href="#projects" className="cta-button">Explore My Work</a>
      </main>

      <div className="cursor" style={{ left: `${mousePosition.x}px`, top: `${mousePosition.y}px` }}></div>

      <style jsx>{`
        .abstract-website {
          font-family: 'Roboto', sans-serif;
          color: #e0e0e0;
          min-height: 100vh;
          position: relative;
          overflow: hidden;
          background: #0f0f1a;
          cursor: none;
        }

        .background {
          position: fixed;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          z-index: 1;
        }

        .shape {
          position: absolute;
          transition: all 0.5s ease;
        }

        .square {
          background: #3498db;
        }

        .circle {
          background: #e74c3c;
          border-radius: 50%;
        }

        .triangle {
          width: 0 !important;
          height: 0 !important;
          border-left: 25px solid transparent;
          border-right: 25px solid transparent;
          border-bottom: 50px solid #2ecc71;
        }

        .line {
          background: #f1c40f;
        }

        header {
          position: fixed;
          top: 20px;
          right: 20px;
          z-index: 10;
        }

        .menu-toggle {
          background: none;
          border: none;
          cursor: pointer;
          z-index: 11;
          width: 30px;
          height: 30px;
          position: relative;
        }

        .menu-icon, .menu-icon::before, .menu-icon::after {
          content: '';
          position: absolute;
          width: 30px;
          height: 2px;
          background: #e0e0e0;
          transition: all 0.3s ease;
        }

        .menu-icon::before {
          top: -8px;
        }

        .menu-icon::after {
          bottom: -8px;
        }

        .open .menu-icon {
          transform: rotate(45deg);
        }

        .open .menu-icon::before {
          top: 0;
          transform: rotate(90deg);
        }

        .open .menu-icon::after {
          bottom: 0;
          transform: rotate(90deg);
        }

        .menu-items {
          position: fixed;
          top: 0;
          right: 0;
          height: 100vh;
          width: 250px;
          background: rgba(15, 15, 26, 0.9);
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          transform: translateX(100%);
          transition: transform 0.5s ease;
        }

        nav.open .menu-items {
          transform: translateX(0);
        }

        .menu-items a {
          color: #e0e0e0;
          text-decoration: none;
          margin: 20px 0;
          font-size: 1.2em;
          position: relative;
          overflow: hidden;
        }

        .menu-items a::after {
          content: '';
          position: absolute;
          bottom: 0;
          left: 0;
          width: 100%;
          height: 1px;
          background: #3498db;
          transform: translateX(-100%);
          transition: transform 0.3s ease;
        }

        .menu-items a:hover::after {
          transform: translateX(0);
        }

        .hire-me {
          background: #3498db;
          color: #0f0f1a;
          padding: 10px 20px;
          border-radius: 25px;
          text-decoration: none;
        }

        main {
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;
          height: 100vh;
          text-align: center;
          position: relative;
          z-index: 2;
        }

        .animated-name {
          font-size: 5em;
          font-weight: bold;
          position: relative;
        }

        .char {
          display: inline-block;
          opacity: 0;
          transform: translateY(50px);
          animation: fadeInUp 0.5s forwards;
          animation-delay: calc(var(--char-index) * 0.1s);
        }

        @keyframes fadeInUp {
          to {
            opacity: 1;
            transform: translateY(0);
          }
        }

        p {
          font-size: 1.2em;
          margin: 20px 0;
          letter-spacing: 2px;
        }

        .cta-button {
          background: #3498db;
          color: #0f0f1a;
          padding: 15px 30px;
          border-radius: 25px;
          text-decoration: none;
          font-size: 1.2em;
          margin-top: 30px;
          transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .cta-button:hover {
          transform: scale(1.1);
          box-shadow: 0 0 20px rgba(52, 152, 219, 0.5);
        }

        .cursor {
          width: 20px;
          height: 20px;
          border: 2px solid #3498db;
          border-radius: 50%;
          position: fixed;
          pointer-events: none;
          z-index: 9999;
          transition: 0.1s;
          transform: translate(-50%, -50%);
        }

        @media (max-width: 768px) {
          .animated-name {
            font-size: 3em;
          }
        }
      `}</style>
      <style jsx global>{`
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;700&display=swap');
        
        body {
          margin: 0;
          padding: 0;
          box-sizing: border-box;
        }
      `}</style>
    </div>
  );
};

export default AbstractWebsite;
