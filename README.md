jsx
import React from 'react';
import { animated, useSpring } from 'react-spring';

const styles = {
  body: {
    backgroundColor: "black",
    display: "flex",
    alignItems: "center",
    justifyContent: "center",
    height: "100vh",
  },
  comingSoon: {
    fontFamily: "'Helvetica', sans-serif",
    color: "white",
    fontSize: "4em",
  },
}

const ComingSoon = () => {

  const animProps = useSpring({
    from: { opacity: 0 },
    to: { opacity: 1 },
    config: {
      duration: 5000
    }
  });

  return (
    <animated.div style={{ ...styles.comingSoon, ...animProps}}>... it's coming</animated.div>
  );
}

export default ComingSoon;
