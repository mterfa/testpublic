# testpublic

   - name: "Launch mysql"
      docker_container:
        name: "gitb-mysql"
        imageasd
        ports:
          - "asdassdsa"
        volumes:
          - "gitb-dbdata:/varasd"
        restart_policy: always
        network_mode: "{{ docker_network }}"
        env:
          MYSQL_ROOT_PASSWORD: root
