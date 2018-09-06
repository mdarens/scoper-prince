# Scoper

A polyfill for scoped HTML style elements, updated to work with [Prince](http://princexml.com/).

# Quick Start

Just include `scoper.js` on your page to start using scoped HTML style elements.

# How It Works

Each `<style scoped>` element's parent is given a unique ID. Its rules are moved to `head` and all selectors prepended with their respective ID.

Scoper is only active when the page contains scoped styles and the browser doesn't support them.

# Tests

Tests can be run with the command `mocha test/test.js`.
