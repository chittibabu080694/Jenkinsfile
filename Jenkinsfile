stage('Deploy via Ansible') {
            steps {
                sh "ansible-playbook ansible/deploy.yml --extra-vars 'image_tag=${IMAGE_TAG}'"
            }
        }
