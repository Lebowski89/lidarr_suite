Lidarr Suite
=========

    Standalone Ansible role to automate the full set-up of Lidarr - a music collection manager for Usenet and BitTorrent users.
      - Includes the installation of Docker (Debian-based distros) and Ansible dependencies within the role.
      - Includes the option of setting up and connecting Lidarr to a Postgres database.
      - Includes the option of setting up Prometheus and a Lidarr Promtheus exporter to gather various metrics about your Lidarr usage and music collection.
      - Includes the option of creating a Cloudflare DNS record for your Lidarr instance for reverse proxy purposes.
      - Includes the option of setting up Autofs NFS (to provide media access on the host system) and Docker NFS volumes (to attach to the Lidarr container).
      - Includes the option of setting up the Rclone Docker plugin and the creation of Rclone Docker volumes (to attach to the Lidarr container).
      - Includes the option of joining Lidarr to an existing Traefik docker network (or creating one if none exists).
      - Includes the option of editing Lidarr's config.xml to include an existing Lidarr API - maintaining connections to other applications that rely on it.

(Proper documentation is coming...)
