@Library('devops-pipelines@main')

import org.emic.devsu.*

/*
 * Mandatory stages: Checkout & Build
 * Mantatory Variables
 *  - Variable Name: projectType 
 *      - String
 *      - Posible values: springboot, nodejs or django
 * TESTING (Optional Stage): 
 *  - You decide if use test Variable. If you want test:
 *    - Variable Name: test
 *          - Array[Boolean, Boolean, Boolean] 
 *          - Each Boolean:
 *              - [0] => Unit Tests
 *              - [1] => Acceptance Tests
 *              - [2] => Integration Tests
 * CODE ANALYSIS (Optional Stage): 
 *  - You decide if use codeAnalysis Variable. If you want test:
 *    - Variable Name: codeAnalysis
 *          - Boolean
 * 
*/
mainPipeline {
    projectType = "nodejs"
    test = [true, true, true]
    codeAnalysis = true
    codeCoverage = true
    delivery = true
    deploy = true
}
