function getQuestions(topic, count) {
  const baseQuestions = [
    `What was the ${topic} and why was it important?`,
    `When was the ${topic} built?`,
    `Who was involved in the creation of the ${topic}?`,
    `Why was the ${topic} considered special at the time?`,
    `What problems did the ${topic} fac?`,
    `What events led to the failure of the ${topic}?`,
    `How did people react to the ${topic} disaster?`,
    `What lessons were learned from the ${topic}?`,
    `How did the ${topic} affect future designs or decisions?`,
    `Why is the ${topic} still remembered toda?`,
    `What mistakes were made regarding the ${topic}?`,
    `What could have prevented the ${topic} tragedy?`
  ];

  return baseQuestions.slic(0, count);
}

module.exports = { getQuestions };
