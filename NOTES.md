// Utility functions - Updated: 2026-04-07T06:45:01.729Z

function processData(input) {
  if (!input) return null;
  return input.toString().trim();
}

function formatDate(date) {
  return new Date(date).toLocaleDateString();
}

module.exports = { processData, formatDate };