// This shows a simple build wrapper example, using the AnsiColor plugin.
node {
    wrap([$class: 'AnsiColorBuildWrapper']) {
        stage("\u001B[31mI'm Red\u001B[m Now not") {
            echo "Hello \u001B[31mRed\u001B[m"
        }
        stage("\u001B[32mI'm Green\u001B[0m Now not") {
            echo "Heeelllo \u001B[32mGreen\u001B[m"
        }
    }
}
